<template>
    <div style="height:100%">
       <my-header></my-header>
       <div class="container index">
            <div class="row">
                 <div class="col-xs-16 main">
                       <!-- 热门专题 -->
                       <div class="recommend-collection">
                           <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_1.jpg" alt="">
                               <span>故事</span>
                           </nuxt-link>
                             <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_2.jpg" alt="">
                               <span>摄影</span>
                           </nuxt-link>
                             <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_3.jpg" alt="">
                               <span>人文社科</span>
                           </nuxt-link>
                             <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_4.jpg" alt="">
                               <span>历史</span>
                           </nuxt-link>
                            <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_5.jpg" alt="">
                               <span>读书</span>
                           </nuxt-link>

                           <nuxt-link class="more-collection" to="/">
                               更多热门专题
                               <i class="fa fa-angle-right"></i>
                           </nuxt-link>

                       </div>
                       <div class="split-line">
                       </div>
                       <!-- 文章列表 -->
                       <div class="list-container">
                           <ul class="note-list">
                               <li class="have-img">
                                <nuxt-link to="/p/123" class="wrap-img">
                                    <img src="~/assets/img/note.jpg" alt="">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                            <nuxt-link to="/p/123" class="avatar">
                                                <img src="~/assets/img/default-avatar.jpg" alt="">
                                            </nuxt-link>
                                             <div class="info">
                                        <nuxt-link to="/u/123" class="nickname">
                                            测试用户
                                        </nuxt-link>
                                        <span class="time">
                                            04.12 10:18
                                        </span>
                                    </div>
                                </div>
                                   
                                    <div class="title">
                                        <nuxt-link to="/p/123">
                                            佛系程序员的月薪5万指南
                                        </nuxt-link>
                                       
                                    </div>
                                    <div class="abstruct">
                                              再要：萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">
                                            社会与法
                                        </nuxt-link>
                                         <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                         </nuxt-link>
                                           <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                         </nuxt-link>
                                         <span>
                                             <i class="fa fa-heart"></i>
                                             20
                                         </span>
                                     
                                    </div>
                                </div>
                                
                               </li>
                               
                                   <li class="have-img">
                                <nuxt-link to="/p/123" class="wrap-img">
                                    <img src="~/assets/img/note.jpg" alt="">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                            <nuxt-link to="/p/123" class="avatar">
                                                <img src="~/assets/img/default-avatar.jpg" alt="">
                                            </nuxt-link>
                                             <div class="info">
                                        <nuxt-link to="/u/123" class="nickname">
                                            测试用户
                                        </nuxt-link>
                                        <span class="time">
                                            04.12 10:18
                                        </span>
                                    </div>
                                </div>
                                   
                                    <div class="title">
                                        <nuxt-link to="/p/123" >
                                            佛系程序员的月薪5万指南
                                        </nuxt-link>
                                       
                                    </div>
                                    <div class="abstruct">
                                              再要：萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">
                                            社会与法
                                        </nuxt-link>
                                         <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                         </nuxt-link>
                                           <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                         </nuxt-link>
                                         <span>
                                             <i class="fa fa-heart"></i>
                                             20
                                         </span>
                                     
                                    </div>
                                </div>
                                
                               </li>
                           </ul>
                          
                       </div>
                       <a href="#" class="load-more">阅读更多</a>
                 </div>
                 <div class="col-xs-offset-1 col-xs-7 aside">
                   <div class="row">
                       <!-- 广告 -->
                      <div class="board">
                          <nuxt-link to="/">
                              <img src="~/assets/img/ad1.png" alt="">
                          </nuxt-link>
                           <nuxt-link to="/">
                              <img src="~/assets/img/ad2.png" alt="">
                          </nuxt-link>
                           <nuxt-link to="/">
                              <img src="~/assets/img/ad3.png" alt="">
                          </nuxt-link>
                           <nuxt-link to="/">
                              <img src="~/assets/img/ad4.png" alt="">
                          </nuxt-link>
                     </div>
                    <!-- 推荐作者 -->
                     <div class="recommended-author">
                         <div class="title">
                              <span>推荐作者</span>
                              <nuxt-link to="/" class="page-change">
                            <i :class="[f?'fa fa-refresh bb':'fa fa-refresh aa']" @click="f=!f"></i>
                                        换一批
                              </nuxt-link>
                         </div>
                         <ul class="recommended-list">
                              <li>
                                  <nuxt-link class="avatar" to="/u/123">
                                      <img src="~/assets/img/default-avatar.jpg" alt="">
                                  </nuxt-link>
                                  <a href="#" :class="[a?'follow':'follow-a']" v-on:click="a=!a" v-on:mouseenter="b=!b" v-on:mouseleave="b=!b">
                                      <i :class="[a?'fa fa-plus':b?'fa fa-check-square-o':'fa fa-close']"></i>
                                      {{a?"关注":b?"已关注":"取消关注"}}                            
                                  </a>
                                  <nuxt-link to="/u/123" class="name">
                                      简书用户
                                  </nuxt-link>
                                   <p>写了1958k字.1.9k喜欢</p>
                                 
                              </li>
                               <li>
                                  <nuxt-link class="avatar" to="/u/123">
                                      <img src="~/assets/img/default-avatar.jpg" alt="">
                                  </nuxt-link>
                                  <a href="#" class="follow" >
                                      <i class="fa fa-plus"></i>
                                        关注
                                  </a> 
                                  <nuxt-link to="/u/123" class="name">
                                      简书用户
                                  </nuxt-link>
                                   <p>写了1958k字.1.9k喜欢</p>
                                 
                              </li>
                               <li>
                                  <nuxt-link class="avatar" to="/u/123">
                                      <img src="~/assets/img/default-avatar.jpg" alt="">
                                  </nuxt-link>
                                  <a href="#" class="follow" >
                                      <i class="fa fa-plus" >关注</i>
                                    
                                  </a>
                                  <nuxt-link to="/u/123" class="name">
                                      简书用户
                                  </nuxt-link>
                                   <p>写了1958k字.1.9k喜欢</p>
                                 
                              </li>
                               <li>
                                  <nuxt-link class="avatar" to="/u/123">
                                      <img src="~/assets/img/default-avatar.jpg" alt="">
                                  </nuxt-link>
                                  <a href="#" class="follow">
                                      <i class="fa fa-plus">关注</i>
                                   
                                  </a>
                                  <nuxt-link to="/u/123" class="name">
                                      简书用户
                                  </nuxt-link>
                                   <p>写了1958k字.1.9k喜欢</p>
                                 
                              </li>
                               <li>
                                  <nuxt-link class="avatar" to="/u/123">
                                      <img src="~/assets/img/default-avatar.jpg" alt="">
                                  </nuxt-link>
                                  <a href="#" class="follow">
                                      <i class="fa fa-plus">关注</i>
                                
                                  </a>
                                  <nuxt-link to="/u/123" class="name">
                                      简书用户
                                  </nuxt-link>
                                   <p>写了1958k字.1.9k喜欢</p>
                                 
                              </li>
                         </ul>
                         <nuxt-link to="/" class="find-more">
                              <p>查看全部></p>
                         </nuxt-link>
                     </div>
                   </div>
                 </div>

            </div>
       </div>
    </div>
</template>
<script>
    import myHeader from  '../components/myHeader'
    export default {
        head:{
            title:'简书-创作你的创作',
            meta:[
                {charset:'utf-8'},
                {name:'keywords',content:'简书首页'},
                {name:'description',content:'简书首页'},
                {name:'author',content:'李志远'}
            ]
        },
        components:{
            myHeader
        },
        data () {
            return {
                name:'首页',
                f:true,
                b:true,
                a:true
               
            }
        },
       mounted:function(){
      
       }
    }
</script>
<style>

</style>