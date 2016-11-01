# ionic 指令（首页index文件）
 - ion-nav-bar 头部
    - bar-positive 颜色修饰
 - ion-nav-back-button 头部返回箭头
 - ion-nav-view 视图模板

# 其他页面 指令
- checkbox (单选框、复选框)


     <pre>
            <ion-view class="MoreMenuPageStyle">
                <ion-nav-title>checkbox</ion-nav-title>
                    <ion-content has-bouncing="false" scrollbar-y="false">
                    <ion-list>
                        <ion-checkbox ng-model="filter.red">Red</ion-checkbox>
                        <ion-checkbox ng-model="filter.yellow">Yellow</ion-checkbox>
                        <ion-checkbox ng-model="filter.pink">Pink</ion-checkbox>
                    </ion-list>

                    <ion-list class="bgImg">
                        <ion-checkbox ng-model="filter1.red">Red</ion-checkbox>
                        <ion-checkbox ng-model="filter1.yellow">Yellow</ion-checkbox>
                        <ion-checkbox ng-model="filter1.pink">Pink</ion-checkbox>
                    </ion-list>
                </ion-content>
             </ion-view>
     </pre>
 - card （头像+文字 面板）


     <pre>
            <ion-view class="MoreMenuPageStyle">
                <ion-header-bar align-title="center" class="bar-stable ">
                    <div class="buttons">
                      <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                    </div>
                      <h1 class="title">card</h1>
                  </ion-header-bar>
                <ion-content>
                    <ion-list  show-delete="shouldShowDelete" show-reorder="shouldShowReorder"  can-swipe="listCanSwipe">
                        <div class="item item-avatar">
                             <img src="images/2.jpg" >
                             <h2>Marrty McFly</h2>
                             <p>Novermber 05,1955</p>
                         </div>
                         <div class="item item-body">
                             <img class="full-image ck-h" src="images/3.jpg">
                             <p>
                                 This is a "FaceBook" styled Card.The header is created from a Thumbernail list Ite,,
                                 The content is from a card-body consisting of an image and paragraph text.the footer
                                 consists of tabs,icons aligned left,within the card-footer.
                             </p>
                             <p>
                                 <a href="#" class="subdued">1 Like</a>
                                 <a href="#" class="subdued">5 Comments</a>
                             </p>
                         </div>
                    </ion-list>
                </ion-content>
             </ion-view>
     </pre>

 - form（表单 包括搜索框 input框）


    <pre>
            <ion-view class="MoreMenuPageStyle">
                <ion-header-bar align-title="center" class="bar-stable ">
                    <div class="buttons">
                      <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                    </div>
                      <h1 class="title">form</h1>
                  </ion-header-bar>
                <ion-content>
                    <div class="bar bar-header item-input-inset">
                        <label class="item-input-wrapper">
                            <i class="icon ion-ios-search placeholder-icon"></i>
                            <input type="search" placeholder="search">
                        </label>
                       <!--  <button class="button button-clear">
                            Cancle
                        </button> -->
                    </div>
                    <div class="list list-inset">
                        <label class="item item-input">
                            <input type="text" placeholder="please enter your name">
                        </label>
                        <label class="item item-input">
                            <input type="password" placeholder="please enter your password">
                        </label>
                    </div>
                    <div class="btn ck-pad">
                        <button class="button button-block button-positive">
                            submit
                        </button>
                    </div>
                </ion-tabs>
                </ion-content>
             </ion-view>
    </pre>
 - header (头像列表页)


     <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-header-bar align-title="center" class="bar-royal ">
                  <div class="buttons">
                    <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                  </div>
                  <h1 class="title">header</h1>
                  <div class="buttons">
                    <button class="button icon-right ion-ios-more button-icon"></button>
                  </div>
              </ion-header-bar>
              <ion-nav-title>header</ion-nav-title>
            <ion-content>
                <div class="list">
                    <a class="item item-thumbnail-left" href="#">
                        <img src="images/4.jpg">
                        <h2>Pretty Machine</h2>
                        <p>The god is a girl</p>
                    </a>
                    <a class="item item-thumbnail-left" href="#">
                        <img src="images/1.jpg">
                        <h2>Green Day</h2>
                        <p>The god is a girl</p>
                    </a>
                    <a class="item item-thumbnail-left" href="#">
                        <img src="images/2.jpg">
                        <h2> Weezer</h2>
                        <p>The god is a girl</p>
                    </a>
                    <a class="item item-thumbnail-left" href="#">
                        <img src="images/3.jpg">
                        <h2> Samping pumpkins</h2>
                        <p>The god is a girl</p>
                    </a>
                    <a class="item item-avatar" href="#">
                       <img src="images/1.jpg">
                       <h2>Venkman</h2>
                       <p>Back off,man.I'm a scientsist.</p>
                   </a>
                   <a class="item item-avatar" href="#">
                       <img src="images/2.jpg">
                       <h2>Venkman</h2>
                       <p>Back off,man.I'm a scientsist.</p>
                   </a>
                   <a class="item item-avatar" href="#">
                       <img src="images/3.jpg">
                       <h2>Venkman</h2>
                       <p>Back off,man.I'm a scientsist.</p>
                   </a>
            </div>
            </ion-content>
            <ion-footer-bar align-title="center" class="bar-royal">
                  <div class="buttons">
                    <button class="button ion-home button-icon icon"></button>
                  </div>
                  <h1 class="title">footer</h1>
                  <div class="buttons" ng-click="doSomething()">
                    <button class="button button-icon icon ion-chatbubble"></button>
                  </div>
            </ion-footer-bar>
         </ion-view>
     </pre>
 - icons（icon应用）


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-header-bar align-title="center" class="bar-stable ">
                <div class="buttons">
                  <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                </div>
                  <h1 class="title">icons</h1>
              </ion-header-bar>
            <ion-content>
                <ion-list  show-delete="shouldShowDelete" show-reorder="shouldShowReorder"  can-swipe="listCanSwipe">
                    <a class="item item-icon-left" href="#">
                       <i class="icon ion-email"></i>Check mail
                   </a>
                   <a class="item item-icon-left item-icon-right" href="#">
                       <i class="icon ion-chatbubble-working"></i>Call me
                       <i class="icon ion-ios-telephone-outline"></i>
                   </a>
                   <a class="item item-icon-left" href="#">
                       <i class="icon ion-mic-a"></i>Record album
                       <span class="item-note">Grammy</span>
                   </a>
                   <a class="item item-icon-left" href="#">
                       <i class="icon ion-person-stalker"></i>Friends
                       <span class="badge badge-assertive">0</span>
                   </a>
                </ion-list>
            </ion-content>
         </ion-view>
    </pre>
 - list(目录列表)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-header-bar align-title="center" class="bar-stable ">
                <div class="buttons">
                    <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                </div>
                <h1 class="title">list</h1>
            </ion-header-bar>
            <ion-nav-title>list</ion-nav-title>
            <ion-content>
                <!-- <ion-list>
                  <ion-item ng-repeat="item in items">
                    Hello, {{item}}!
                  </ion-item>
                </ion-list> -->
                <ion-list show-delete="flag.showDelete" show-reorder="flag.showRecorder" can-swipe="true">
                    <ion-item ng-repeat="item in items" class="item-thumbnail-left">
                        <img ng-src="{{item.img}}">
                        <h2>{{item.title}}</h2>
                        <p>{{item.description}}</p>
                        <ion-option-button class="button-positive icon ion-share" ng-click="share(item)">
                            分享
                        </ion-option-button>
                        <ion-option-button class="button-info icon ion-edit" ng-click="edit(item)">
                            编辑
                        </ion-option-button>
                        <ion-delete-button class="ion-minus-circled" ng-click="items.splice($index, 1)">
                        </ion-delete-button>
                        <ion-reorder-button class="ion-navicon" on-reorder="reorderItem(item, $fromIndex, $toIndex)">
                        </ion-reorder-button>
                    </ion-item>
                </ion-list>
            </ion-content>
            <ion-footer-bar align-title="center" class="bar-royal">
                  <div class="buttons">
                    <button class="button button-icon ion-ios-minus-outline icon" ng-click="flag.showDelete=!flag.showDelete;falg.showRecorder=false;"></button>
                  </div>
                  <h1 class="title">footer</h1>
                  <div class="buttons" ng-click="flag.showRecorder=!flag.showRecorder;flag.showDelete=false;">
                    <button class="button button-icon icon ion-navicon"></button>
                  </div>
            </ion-footer-bar>
        </ion-view>
    </pre>
 - sidemenu (左右菜单框切换)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-nav-title>sidemenu</ion-nav-title>
            <!-- style1 -->
            <!-- <ion-side-menus>
                <ion-side-menu-content class="calm-bg">
                    <ion-nav-title>header</ion-nav-title>
                    <ion-content has-subheader="false" class="positive-bg">
                        <a menu-toggle="left" class="button icon ion-navicon"></a>
                        <a menu-close="" class="button icon ion-navicon"></a>
                    </ion-content>
                </ion-side-menu-content>
                <ion-side-menu side="left" width="100" class="balanced-bg" expose-aside-when="(min-width:300px)">
                    left area
                </ion-side-menu>
            </ion-side-menus> -->
            <!-- style2 -->
             <ion-side-menus>
                <ion-side-menu-content class="calm-bg">
                    <ion-nav-title>header</ion-nav-title>
                    <ion-content has-subheader="false" class="positive-bg">
                        <a menu-toggle="left" class="button icon ion-chevron-left"></a>
                        <a menu-close="" class=" button icon ion-close-round"></a>
                        <a  class="button icon ion-chevron-right" ng-click="toggle()"></a>
                    </ion-content>
                </ion-side-menu-content>
                <ion-side-menu side="left" width="100" class="balanced-bg">
                    left area
                </ion-side-menu>
                <ion-side-menu side="right" class="energized-bg" width="200">
                    right area
                </ion-side-menu>
            </ion-side-menus>
        </ion-view>
    </pre>
 - tabs (tab切换)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-nav-title>{{title}}</ion-nav-title>
            <!-- style1 -->
             <ion-tabs class="tabs-positive tabs-icon-only">
                <ion-tab title="Tab1" on-select="on_select(1)">
                    <ion-view view-title="Your Title!" class="calm-bg">
                        <h2>tab1 content</h2>
                    </ion-view>
                </ion-tab>
                <ion-tab title="Tab2" on-select="on_select(2)">
                    <ion-view view-title="Your Title!" class="balanced-bg">
                        tab2 content
                    </ion-view>
                </ion-tab>
                <ion-tab title="Tab3" on-select="on_select(3)">
                    <ion-view view-title="Your Title!" class="energized-bg">
                        tab1 content
                    </ion-view>
                </ion-tab>
            </ion-tabs>
            <!-- style2 -->
            <!-- <ion-tabs class="tabs-positive tabs-icon-only tabs-striped tabs-top">
                <ion-tab title="Tab1">
                    <ion-view class="calm-bg">
                        tab1 content
                    </ion-view>
                </ion-tab>
                <ion-tab title="Tab2">
                    <ion-view view-title="Your Title!" class="balanced-bg">
                        tab2 content
                    </ion-view>
                </ion-tab>
                <ion-tab title="Tab3">
                    <ion-view view-title="Your Title!" class="energized-bg">
                        tab1 content
                    </ion-view>
                </ion-tab>
            </ion-tabs> -->
            <!-- style3 -->
           <!--  <ion-tabs class="tabs-positive tabs-icon-top">
                <ion-tab title="Home" icon-on="ion-android-favorite" icon-off="ion-android-favorite-outline ">
                    <ion-nav-title>tabs</ion-nav-title>
                    <ion-content>
                        <p>home content</p>
                    </ion-content>
                </ion-tab>
                <ion-tab title="eamil" icon-on="ion-ios-email" icon-off="ion-ios-email-outline " badge="12" badge-style="badge-assertive">
                    <ion-nav-title>tabs</ion-nav-title>
                    <ion-content>
                        <p>email content</p>
                    </ion-content>
                </ion-tab>
                <ion-tab title="clock" icon-on="ion-ios-clock" icon-off="ion-ios-clock-outline ">
                    <ion-header-bar class="bar-positive">
                        <h1 class="title">clock tab</h1>
                    </ion-header-bar>
                    <ion-content>
                        <p>clock content</p>
                    </ion-content>
                </ion-tab>
            </ion-tabs> -->
        </ion-view>
    </pre>
 - actionsheet (完美的tab切换)


    <pre>
        <ion-view class="MoreMenuPageStyle" hide-nav-bar="true" >

            <ion-tabs class="tabs-positive tabs-icon-top">
              <ion-tab title="首页" icon-on="ion-ios-filing" icon-off="ion-ios-filing-outline">
                  <div class="row">
                     <div class="col">
                           <div ng-click="show()">测试</div>
                     </div>
                     <div class="col">
                           <div ng-click="show()">测试</div>
                     </div>
               </div>
              </ion-tab>
              <ion-tab title="关于" icon-on="ion-ios-clock" icon-off="ion-ios-clock-outline" >
                  <ion-spinner class="spinner-energized" icon="ios"></ion-spinner>
                  <hr />
                  <button class="button" ng-click="selectTabWithIndex(2)">进入设置页面</button>
              </ion-tab>
              <ion-tab title="设置" icon-on="ion-ios-gear" icon-off="ion-ios-gear-outline">
                <ion-slide-box does-continue="true" auto-play="true" slide-interval="2000">
                  <ion-slide>
                    <div class="box blue"><h1>BLUE</h1></div>
                  </ion-slide>
                  <ion-slide>
                    <div class="box yellow"><h1>YELLOW</h1></div>
                  </ion-slide>
                  <ion-slide>
                    <div class="box pink"><h1>PINK</h1></div>
                  </ion-slide>
                </ion-slide-box>
                <hr />
                <button class="button" ng-click="selectTabWithIndex(0)">进入首页</button>
              </ion-tab>
          </ion-tabs>
         </ion-view>



        <ion-view class="MoremenuPageStyle" hide-nav-bar="true">
            <ion-tabs class="tab-positive tabs-icon-top">
                <ion-tab title="首页" icon-on="ion-ios-filing" off="ion-ios-filing-outline">
                    <div class="row">
                        <div class="col">
                            <div ng-click="show()">测试</div>
                        </div>
                        <div class="col">
                            <div ng-click="show()">测试</div>
                        </div>
                    </div>
                </ion-tab>
                <ion-tab title="关于" icon-on="ion=ios-clock" icon-off="ion-ios-clock-outline">
                    <ion-spinner class="spinner-energized" icon="ios"></ion-spinner>
                    <hr/>
                    <button class="button" ng-click="selectTabWithIndex(2)">进入设置页面</button>
                </ion-tab>
                <ion-tab title="设置" icon-on="ion-ios-gear" icon-off="ion-ios-gear-outline">
                    <ion-slide-box does-continue="true" auto-play="true" slide-interval="2000">
                        <ion-slide>
                            <div class="box blue"><h1>BLUE</h1></div>
                        </ion-slide>
                        <ion-slide class="box yellow"><h1>YELLOW</h1></ion-slide>
                        <ion-slide class="box pink"><h1>PINK</h1></ion-slide>
                    </ion-slide-box>
                    <hr/>
                    <button class="button" ng-click="selectedTabIndex(0)">进入首页</button>
                </ion-tab>
            </ion-tabs>
        </ion-view>
    </pre>
 - anchorScroll (滚动条滑动)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-header-bar align-title="center" class="bar-stable ">
                <div class="buttons">
                  <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                </div>
                  <h1 class="title">anchorScroll</h1>
              <div class="buttons">
                <button class="button button-icon icon ion-clock" ng-click="doScroll()"></button>
              </div>
              </ion-header-bar>
            <ion-content>
                <ion-list>
                    <ion-item ng-repeat="item in items" id="foo-{{item.id}}" href="#/item/{{item.id}}">
                      Item {{ item.id }}
                    </ion-item>
              </ion-list>
            </ion-content>
         </ion-view>
    </pre>
 - clickTest (滑动开关 单选框  复选框测试)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-header-bar align-title="center" class="bar-stable ">
                <div class="buttons">
                  <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                </div>
                  <h1 class="title">clickText</h1>
              </ion-header-bar>
              <nav id="tab-bar" class="tabs tabs-icon-top">
                     <a class="tab-item" href="#">
                       <i class="icon ion-android-contact"></i>
                       Fun
                     </a>
                     <a class="tab-item">
                       <i class="icon ion-locked"></i>
                       Security
                     </a>
                     <a class="tab-item">
                       <i class="icon ion-heart"></i>
                       Simple
                     </a>
                     <a class="tab-item">
                       <i class="icon ion-leaf"></i>
                       Light
                     </a>
                     <a class="tab-item">
                       <i class="icon ion-waterdrop"></i>
                       Clean
                     </a>
             </nav>
            <ion-content>
                <div ng-show="testBtnText == 'HTML'">
                    <ion-list>
                        <div class="item" on-swipe="gestureTest($event, 'swipe (any direction)')">
                        Swipe (any direction)
                      </div>
                      <div class="item" on-swipe-left="gestureTest($event, 'swipe left')">
                        Swipe Left
                      </div>
                      <div class="item" on-swipe-right="gestureTest($event, 'swipe right')">
                        Swipe Right
                      </div>
                    </ion-list>
                    <div id="box" class="box">
                        <span id="output"></span>
                    </div>

                </div>
              <div ng-show="testBtnText == 'AngJS'">
                 <div class="list">
                      <div class="item item-toggle">
                         HTML5
                         <label class="toggle">
                           <input type="checkbox">
                           <div class="track">
                             <div class="handle"></div>
                           </div>
                         </label>
                      </div>
                      <div class="item item-toggle">
                         JavaScript
                         <label class="toggle">
                           <input type="checkbox" ng-click="htmlToggleClick()">
                           <div class="track">
                             <div class="handle"></div>
                           </div>
                         </label>
                      </div>
                      <ion-list>
                          <ion-radio ng-model="choice" ng-value="'A'">Choose A</ion-radio>
                          <ion-radio ng-model="choice" ng-value="'B'">Choose B</ion-radio>
                    </ion-list>

                    <ion-checkbox ng-model="htmlCheckboxData.checkedValue">Checkbox {{ htmlCheckboxData.checkedValue }}</ion-checkbox>


                  </div>
                </div>
                <button ng-click="otherTests()">{{ testBtnText }}</button>
            </ion-content>
         </ion-view>
    </pre>
 - loading (没功能 loading图标)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-header-bar align-title="center" class="bar-stable ">
                <div class="buttons">
                    <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                </div>
                <h1 class="title">loading</h1>
            </ion-header-bar>
            <ion-nav-title>loading</ion-nav-title>
            <ion-content>
                <div class="button icon ion-refresh" ng-click="load()">载入</div>
                <ion-list ng-repeat="item in items">{{item}}</ion-item>
                </ion-list>
            </ion-content>
        </ion-view>
    </pre>
 - model(点击实现模态框)&mymodel(弹出模态框)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-header-bar align-title="center" class="bar-stable ">
                <div class="buttons">
                    <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                </div>
                <h1 class="title">modal</h1>
            </ion-header-bar>
            <ion-content>
                <div class="button" ng-click="openModal()">打开模态对话框</div>
            </ion-content>
        </ion-view>
    </pre>
    <pre>
        <ion-modal-view>
        	<ion-content has-subheader="false">
        		<div class="padding">
        			<div class="list">
        				<label class="item item-input">
        					<span class="input-lable">
        						FirstName
        					</span>
        					<input ng-model="newUser.firstName" type="text">
        				</label>
        				<label class="item item-input">
        					<span class="input-lable">
        						LastName
        					</span>
        					<input ng-model="newUser.lastName" type="text">
        				</label>
        				<label class="item item-input">
        					<span class="input-lable">
        						Email
        					</span>
        					<input ng-model="newUser.email" type="text">
        				</label>
        				<button class="button button-full button-positive" ng-click="createContact">Create</button>
        				<a class="button" ng-click="closeModal()">关闭</a>
        				<a class="button" ng-click="removeModal()">remove</a>
        			</div>
        		</div>
        </ion-content>
        </ion-modal-view>
    </pre>
 - popover(点击帮助)& popover (弹出帮助内容)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-header-bar align-title="center" class="bar-stable ">
                <div class="buttons">
                    <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                </div>
                <h1 class="title">popover</h1>
            </ion-header-bar>
            <ion-content>
                <div class="button" ng-click="openPopover($event)">帮助</div>
            </ion-content>
        </ion-view>
    </pre>
    <pre>
        <ion-popover-view class="calm-bg light padding">
        	<p>这里应该有些帮助信息。。。。。</p>
        </ion-popover-view>
    </pre>
 - popup(展示一些弹出框 showPopup、showAlert、showConfirm、showPrompt)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-header-bar align-title="center" class="bar-stable ">
                <div class="buttons">
                    <button class="button button-icon icon ion-ios-arrow-left" ng-click="goTo()"></button>
                </div>
                <h1 class="title">popup</h1>
            </ion-header-bar>
            <ion-content>
                <div class="button" ng-click="showPopup()">showPopup</div>
                <button ng-click="showAlert()" class="button">showAlert</button>
                <div class="button" ng-click="showConfirm()">showConfirm</div>
                <button ng-click="showPrompt()" class="button">showPrompt</button>
            </ion-content>
        </ion-view>
    </pre>
 - slidebox(轮播图)


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-nav-title>slidebox</ion-nav-title>
            <ion-content>
            <!-- auto-play="true" 自动播放幻灯片 -->
                <ion-slide-box does-continue="true" show-pager="true"
                on-slide-changed="go_changed(index)" active-slide="index" pager-click='go(index)'>
                    <ion-slide>
                        <img src="images/1.jpg">
                    </ion-slide>
                    <ion-slide>
                        <img src="images/2.jpg">
                    </ion-slide>
                    <ion-slide>
                        <img src="images/3.jpg">
                    </ion-slide>
                    <ion-slide>
                        <img src="images/4.jpg">
                    </ion-slide>
                </ion-slide-box>
                <button class="button" ng-click="go_next()">next</button>
                 <button class="button" ng-click="go_previous()">previous</button>
            </ion-content>
        </ion-view>

    </pre>

 - select(弹出单选、多选)


    <pre>
        <ion-view>
        	<ion-nav-title>select</ion-nav-title>
        	<ion-content has-bouncing="false" scrollbar-y="false">
        	    <div class="list">
        	      <mr-select class="selectNav-bd" select-opentions='selectArr' select-value='selectId' select-changed='showRes(info)' select-data='selectInfo' ng-bind='selectInfo'></mr-select>
        			<mr-multi-select class="selectNav-bd" select-opentions='selectArr1' select-value='selectArr' select-changed='showRes(info)' select-data='selectInfo1'>
        				<span ng-repeat="info in selectInfo1" ng-if="info.model">{{info.name}}</span>
        			</mr-multi-select>
        	    </div>
        	</ion-content>
         </ion-view>
    </pre>
    <pre>
        <ion-model-view hide-nav-bar="true">
        	<ion-content has-bouncing="false" scrollbar-y="false" class="selectStyle-bd">
        		<div class="selectBox-lst">
        			<h2 class="title">Which planets have you visited?</h2>
        			<ion-scroll direction="y" scrollbar-x="false" zooming="false" class="selectScroll">
        				 <ion-radio ng-if="!isMulti" ng-model="model1" ng-value="info.name" ng-repeat="info in data" ng-click="goInfo(info);">{{info.name}}</ion-radio>
        				<ion-checkbox ng-if="isMulti" ng-repeat="info in data" ng-click="goInfo(data);" ng-model="info.model">{{info.name}}</ion-checkbox>
        			</ion-scroll>
        			<div class="buttonBar">
        				<span ng-click="remove();">取消</span>
        				<span ng-click="confirm();">确认</span>
        			</div>
        		</div>
        	</ion-content>
        </ion-model-view>
    </pre>
 - toggle（开关按钮）


    <pre>
        <ion-view class="MoreMenuPageStyle">
            <ion-list>
                <ion-toggle ng-model="Wireless" toggle-class="toggle-calm">Wireless</ion-toggle>
                <ion-toggle ng-model="Gps" toggle-class="toggle-calm">Gps</ion-toggle>
                <ion-toggle ng-model="BlueTooth" toggle-class="toggle-calm">BlueTooth</ion-toggle>
            </ion-list>
         </ion-view>
    <pre>


 # app.js(依赖、全局设置（$rootscope、appController)


    <pre>
        angular.module('secoo.app', [
            'maxrocky.framework',
            'secoo.app.config',
            'secoo.common',
            'ionic',
            'secoo.templates',
            'secoo.demo',
            'secoo.demo2',
            // 'secoo.demo3',
            'secoo.common.login',
            'maxrocky.framework.sdk',
            'secoo.common.mocksJS',
            'secoo.select',
            'secoo.checkbox',
            'secoo.toggle',
            'secoo.ionic',
            'secoo.ionicJs'
        ])

        .run(['$rootScope',
            function($rootScope) {
            }
        ])

        .controller('AppController', ['$scope',
            function($scope) {
            }
        ]);
    </pre>

 # demo.js（依赖、ui-rounter、控制器）


    <pre>
        angular.module('secoo.demo', [
            'ionic', 'ionic-datepicker'
        ])

        .config(['$stateProvider', function($stateProvider) {
            $stateProvider.state('demo', {
                url: '/demo',
                controller: 'demoController',
                templateUrl: 'demo/demo.tpl.html',
                authorizedRuleType: ["1", "2", "3", "4", "5"],
            })
        }])

        .controller('demoController', ['MrCamera', '$scope', '$http', '$state',
            function(MrCamera, $scope, $http, $state) {


                $scope.data = {
                    bannerImgList: [
                        { url: "http://secoolive.maxrocky.com/images/hotel/index_02.jpg", href: "/home/mine", id: "1", type: "shangpin" },
                        { url: "http://secoolive.maxrocky.com/images/hotel/index_03.jpg", href: "/home/mine", id: "2", type: "shangpin" },
                        { url: "http://secoolive.maxrocky.com/images/hotel/index_04.jpg", href: "/home/mine", id: "3", type: "shangpin" },
                        { url: "http://secoolive.maxrocky.com/images/hotel/index_02.jpg", href: "/home/mine", id: "4", type: "shangpin" },
                    ],
                }
                $scope.goTo = function () {
                    $state.go('demo2')
                }
                // $scope.goTo3 = function () {
                //     $state.go('demo3')
                // }
                $scope.getPic = function() {
                    MrCamera.getPicture();
                }
                $scope.getSelect = function(){
                    $state.go('select');
                }
            }
        ])
    </pre>

 # 服务及指令（见demo中 mrframework和app里的common）




















