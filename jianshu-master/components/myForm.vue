<template>
   <div>
         <form method="post" class="new-comment">
             <slot></slot>
             <textarea name="comment-content" placeholder="写下你的评论" v-model="value"></textarea>
             <div class="write-function-block">
                <div class="emoji-modal-wrap">
                   <a class="emoji-a" @click="isShow=!isShow">
                    <i class="fa fa-smile-o"></i>
                   </a>
                   <div class="emoji-modal">
                          
                   </div>
                </div>
                 <div class="hint">Ctrl+Enter发送</div>
                 <a href="#" class="btn-send">发送</a>
                 <a href="#" class="btn-cancel">取消</a>
             </div>
              <emoji @select="selectEmoji" v-if="isShow"></emoji>
         </form>
   </div>

</template>

<script>
import emoji from './emoji'
export default {
  name: "myForm",
  data() {
    return {
      value:'',
      isShow:false
    };
  },
  components:{
      emoji
  },
  methods: {
    selectEmoji(code) {
      this.showEmoji = false;
      this.value += code;
    }
  }
};
</script>
