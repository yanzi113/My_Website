<template>
    <div class="min-h-screen bg-gray-200 flex justify-center items-center">
        <div :class="themeClasses" class="p-8 rounded-lg shadow-lg m-4">
            <div class="flex justify-between">
                <h1 class="text-3xl font-bold mb-4">燕子</h1>
                <button @click="toggleTheme">切换主题</button>
            </div>
            <p class=" mb-2">⼥ | 年龄：22岁 | 19231137495 | yanzi7310v0@gmail.com</p>
            <p class=" mb-2">2年⼯作经验 | 求职意向：前端开发⼯程师</p>
            <div class="flex flex-col">
                <div class="flex flex-col">
                    <div class="my-4 w-full h-10 bg-gray-200 bg-opacity-50 border-l-4 flex justify-start items-center"
                        :class="borderClasses">
                        <h2 class="font-semibold text-xl ml-4">专业技能</h2>
                    </div>
                    <div class="">
                        <ol class="list-decimal list-inside">
                            <li>掌握vue3框架以及vue3全家桶(pinia、vue-router4)，Vite</li>
                            <li>掌握vue2 框架及使用 vue2 全家桶(vuex、vue-router)，vue-cli</li>
                            <li>掌握UI框架:Element UI/Element Plus</li>
                            <li>掌握网络通信基础，如axios库，http协议,以及实时通讯协议websocket构建ai平台</li>
                            <li>熟悉HTML、CSS、JavaScript语法基础</li>
                            <li>熟悉Echarts可视化,会使用antV、DataV等可视化工具</li>
                            <li>熟悉tailwind css框架来快速书写样式</li>
                            <li>熟悉git工作流</li>
                            <li>会使用ES6、TypeScript语法基础,CSS 处理器sass scss less</li>
                            <li>了解JavaScript语法进阶,包括:作用域和闭包、this和对象原型等</li>
                            <li>了解react,Node.js,构建工具 Webpack,计算机网络和数据结构,python爬虫、mysql和java，Linux命令</li>
                        </ol>

                    </div>
                </div>
            </div>
            <div class="flex flex-col">
                <div class="flex flex-col">
                    <div class="my-4 w-full h-10 bg-gray-200 bg-opacity-50 border-l-4 flex justify-start items-center"
                        :class="borderClasses">
                        <h2 class="font-semibold text-xl ml-4">工作经历</h2>
                    </div>
                    <div>
                        <ul class="list-none list-inside flex flex-wrap justify-between leading-loose">
                            <li class="flex-none mr-8">
                                <h3 class="text-lg font-semibold">北京神州安付科技股份有限公司</h3>
                            </li>
                            <li class="grow">前端开发⼯程师</li>
                            <li class="flex-none text-right">2022.02-2024.01</li>
                        </ul>
                        <ul class="list-none list-outside ">
                            <li>
                                负责公司产品的前端开发任务，与后端开发⼯程师共同完成设计效果，对新项⽬进⾏配合开发，对⽼项⽬进⾏
                                优化、迭代更新，添加新功能。以Vue3交互为主完成参与公司模块设计。
                            </li>
                            <li>
                                根据⼯作安排，确保代码规范，使⽤插件和第三⽅库辅助项⽬开发，提⾼⼯作效率。
                                与团队配合，开发⾼复⽤组件，设计⽤⼾交互逻辑并实现。
                            </li>
                        </ul>
                    </div>
                    <div class="mt-2.5">
                        <ul class="list-none list-inside flex flex-wrap justify-between leading-loose">
                            <li class="flex-none mr-8 ">
                                <h3 class="text-lg font-semibold">北京觅机科技有限公司</h3>
                            </li>
                            <li class="grow">前端开发⼯程师</li>
                            <li class="flex-none text-right">2024.03-2024.07</li>
                        </ul>
                        <ul>
                            <li>
                                1.负责公司官网项目从0搭建至完成
                            </li>
                            <li>
                                2.负责公司AFH-LED-HW-G1-V1-UI:ai智能生成硬件项目重构及优化、新功能（ai沟通生成需求，用户管理，生成记录）搭建
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="flex flex-col">
                <div class="flex flex-col">
                    <div class="my-4 w-full h-10 bg-gray-200 bg-opacity-50 border-l-4 flex justify-start items-center"
                        :class="borderClasses">
                        <h2 class="font-semibold text-xl ml-4">工作经历</h2>
                    </div>
                    <div id="1" class="mb-2.5">
                        <ul class="list-none list-inside flex flex-wrap justify-between leading-loose">
                            <li class="flex-none mr-8 ">
                                <h3 class="text-lg font-semibold">vue3.2通用后台管理系统</h3>
                            </li>
                            <li class="flex-none text-right">2022.02-2024.01</li>
                            GitHub：https://github.com/yanzi113/Vue_3.2
                            <br>
                            项目介绍：该项目为一个通用后台管理系统，用户可以根据需求用于不同业务的后台管理，主要有用户管理、权限管理、商品管
                            理、订单管理、数据统计等功能
                            <br>
                            技术栈：vue3、vuex、axios、git、element-plus
                            <br>
                            主要负责：
                            <ul>
                                <li>1.登录页面编写：编写登录页面(静态)、配置使用svg自定义图标组件、编写表单校验、登录请求、请求响应拦截器、
                                    localStorage存储token、使用路由守卫实现用户访问限制</li>
                                <li>2.主界面功能编写：主界面layout布局（静态）、menus菜单静态及路由、指定时间被动退出、汉堡按钮伸缩顶、动态面包屑导航、点击头像退出、使用i18n实现中英切换、点击全屏、用户引导
                                </li>
                                <li>3.用户管理功能编写：用户表格（静态）、分页器、添加用户、删除用户、编辑用户等</li>
                            </ul>
                            <ul>
                                技术亮点：
                                <li>1.通过配置代理proxy解决跨域问题</li>
                                <li>2.使用到路由守卫token来解决登录后下一次不用登录就进入主界面</li>
                                <li>3.使用element-plus中的layout布局登录后的主界面</li>
                                <li>4.使用axios的响应拦截器来获取想要的指定响应数据，请求拦截器为每一个接口添加上token信息</li>
                                <li>5.使用driver.js第三方库和相关配置编写实现用户引导</li>
                            </ul>
                        </ul>
                    </div>
                    <div id="2" class="mb-2.5">
                        <ul class="list-none list-inside flex flex-wrap justify-between leading-loose">
                            <li class="flex-none mr-8 ">
                                <h3 class="text-lg font-semibold">Vuex清单</h3>
                            </li>
                            <li class="flex-none text-right">2022.08-2023.01</li>
                            GitHub：https://github.com/yanzi113/Vue_3.2
                            <br>
                            项目介绍：该项目为一个通用后台管理系统，用户可以根据需求用于不同业务的后台管理，主要有用户管理、权限管理、商品管
                            理、订单管理、数据统计等功能
                            <br>
                            技术栈：vue3、vuex、axios、git、element-plus
                            <br>
                            主要负责：
                            <ul>
                                <li>1.登录页面编写：编写登录页面(静态)、配置使用svg自定义图标组件、编写表单校验、登录请求、请求响应拦截器、
                                    localStorage存储token、使用路由守卫实现用户访问限制</li>
                                <li>2.主界面功能编写：主界面layout布局（静态）、menus菜单静态及路由、指定时间被动退出、汉堡按钮伸缩顶、动态面包屑导航、点击头像退出、使用i18n实现中英切换、点击全屏、用户引导
                                </li>
                                <li>3.用户管理功能编写：用户表格（静态）、分页器、添加用户、删除用户、编辑用户等</li>
                            </ul>
                            <ul>
                                技术亮点:
                                <li>1.通过配置代理proxy解决跨域问题</li>
                                <li>2.使用到路由守卫token来解决登录后下一次不用登录就进入主界面</li>
                                <li>3.使用element-plus中的layout布局登录后的主界面</li>
                                <li>4.使用axios的响应拦截器来获取想要的指定响应数据，请求拦截器为每一个接口添加上token信息</li>
                                <li>5.使用driver.js第三方库和相关配置编写实现用户引导</li>
                            </ul>
                        </ul>
                    </div>
                    <div id="3" class="mb-2.5">
                        <ul class="list-none list-inside flex flex-wrap justify-between leading-loose">
                            <li class="flex-none mr-8 min-w-full">
                                <div class="min-w-full flex justify-between">
                                    <h3 class="text-lg font-semibold inline-block">旺旺商城</h3>
                                    <span>2023.04-2023.12</span>
                                </div>
                            </li>
                            <li>
                                GitHub：https://github.com/yanzi113/vue3_wwsc/tree/master
                            <br>
                            项目介绍：该项目为电商平台，用户可以在商城购买各种商品，主要功能包括首页、商品分类、商品详情、购物车和结算支付、 会员中心等
                            <br>
                            技术栈：vue3-setup、pinia、axios、element-plus、vue-router、vueuse、git
                            <br>
                            主要负责：
                            除静态页面以外每个功能的组件交互编写、数据渲染编写、接口请求封装和部分工具类的封装、pinia管理复用的数据 和方法、路由及跳转配置
                            </li>
                        </ul>
                        <ul >
                                技术亮点:
                                <li>1.吸顶导航交互</li>
                                <li>2.图片懒加载自定义指令</li>
                                <li>3.面板插槽组件等业务通用组件</li>
                                <li>4.SKU电商组件使用</li>
                                <li>5.图片组件细节预览</li>
                                <li>6.支付宝三方支付</li>
                                <li>7.pinia用户持久化存储persist</li>
                            </ul>
                    </div>
                    <div id="4" class="mb-2.5">
                        <ul class="list-none list-inside flex flex-wrap justify-between leading-loose">
                            <li class="flex-none mr-8 ">
                                <h3 class="text-lg font-semibold">通用数据大屏可视化</h3>
                            </li>
                            <li class="flex-none text-right">2023.09-2024.01</li>
                            在线预览地址：https://yanzi113.github.io/data_V/
                            <br>
                            GitHub:https://github.com/yanzi113/data-V
                            <br>
                            项目介绍:该项目为各种数据整合的图表可视化，用户可以根据自己需求使用。一共有4部分组成，一共包含11种图，分别为：大
                            区横向柱形图、服务竖向柱形图、报警风险雷达图、异常处理双环形图、数据传递关系图、关键词条文档云图、数据总览图、地图可视化、散点图、动态柱形图、时间轴图
                            <br>
                            技术栈：Vue3、Echarts5、axios、git
                            <br>
                            主要负责:
                            <br>
                            除css编写外各种Echarts图表的配置和使用，接口请求封装，axios响应拦截器来获取指定响应数据，动态渲染数据 至图表，快速打包部署预览
                            <ul>
                                技术亮点:
                                <li>1.通过watch生命周期钩子监听每次数据变化并重新渲染图表（动态渲染）</li>
                                <li>2.使用map方法去筛选每个子组件需要展示的数据</li>
                                <li>3.饼图叠加实现异常处理双环形图</li>
                                <li>4.使用echarts-wordclound和countUp.js第三方库分别实现词云图和数字快速跳动效果</li>
                                <li>5.使用响应拦截器对获取到的数据进行解构和处理请求成功失败情况，确保获取指定数据</li>
                                <li>6.无需购买服务器快速打包部署至GitHub Page预览</li>
                            </ul>
                        </ul>
                    </div>
                    <div id="5" class="mb-2.5">
                        <ul class="list-none list-inside flex flex-wrap justify-between leading-loose">
                            <li class="flex-none mr-8 min-w-full">
                                <div class="min-w-full flex justify-between">
                                    <h3 class="text-lg font-semibold inline-block">深圳指数官网</h3>
                                    <span>2024.03-2024.03</span>
                                </div>
                            </li>
                            <li>
                            项目介绍：该项目为分公司的官网，开发周期为2周，纯前端实现
                            <br>
                            技术栈：vue3,pinia,element-plus,vue-router,git
                            </li>
                        </ul>
                        <ul>
                                技术亮点:
                                <li>1.基于flex布局完成首页、关于我们、产品解决方案、研发创新、新闻中心五个模块</li>
                                <li>2.自适应postcss-px-to-viewport方案，适配不同尺寸设备，还原设计稿比例</li>
                                <li>3.router-link锚点跳转方案，实现页面内跳转</li>
                                <li>4.图片资源优化webP，首屏加载优化方案等</li>
                                <li>5.基于i18n方案实现中英切换功能</li>
                                <li>6.基于element-plus组件库实现菜单，分页，轮播等</li>
                            </ul>
                    </div>
                    <div id="6" class="mb-2.5">
                        <ul class="list-none list-inside flex flex-wrap justify-between leading-loose">
                            <li class="flex-none mr-8 ">
                                <h3 class="text-lg font-semibold">AFH-LED-HW-G1</h3>
                            </li>
                            <li class="flex-none text-right">2024.03-2024.07</li>
                            项目介绍：该项目深圳指数- AI智能生成硬件-的项目，项目主要为：登陆模块（权限管理）、生成模块、跟AI沟通生成需求模 块、用户管理模块（仅管理员可见）、生成记录模块
                            <br>
                            技术栈：vue2,websocket,sessionStorage,canvas,element ui
                            <ul>
                                主要负责：
                                <li>1.项目总体样式重构和优化，迁移合并至4.19项目初始版本</li>
                                <li>2.登陆模块重构和优化：登录后根据权限（用户，管理员）做资源分配和跳转，可登出<br>(1)用户：1、加载逻辑为新接口，加载页面会有
                                    “图纸开始生成，可在左侧生成记录中查看进度”文字显示2、预览模式：可预
                                    览进行生成中流程、已完成流程（下载）<br>(2)管理员：1、用户管理功能，可添加和删除用户。2、预览模式：只可预览用户已完成状态流程下文件（下载） </li>
                                <li>3.需求合成文件功能优化和重构<br>(1)上传excel需求文件表格预览重构优化<br>(2)Dxf
                                    按键判断和Excel需求文件按键判断（前端）通过才可进行合成<br>(3)点击“开始启动生成”前通过“获取系统运行状态”接口和按键是否匹配判断是否可运行，均有提示<br>(4)进度条相关逻辑重构和优化：具体为进度条1加载完毕获取图纸雪花图展示->进度条2加载完毕获取文件下载链接
                                </li>
                                <li>4.跟AI沟通需求文件功能优化和重构<br>(1)总体ui优化：自适应响应式，底部输入动态渐变动画，按钮，上传附件等<br>(2)ai沟通逻辑重构优化：由http更换为websocket实时展示ai输出内容，以及ai初始默认发送一条消息，未输入不可生成需求文件<br>(3)生成需求文件功能：1.预览需求文件表格：表格由ai后端接口内容返回：可修改编辑每项和保存。2.确认需求文件并上传DXF
                                    图纸：确定完需求文件，自动上传至“需求合成文件”功能模块。3.和ai沟通需求：如用户不满意当前生成表格，可根据之前沟
                                    通内容继续生成。4.下载需求：前端生成沟通完毕需求对应的excel文件，用户点击即可下载。</li>
                                <li>5.用户管理（仅管理员可见）<br>(1)可知晓姓名、角色、创建时间和操作的内容等<br>(2)可添加/删除对应角色的对应用户,均有提示</li>
                                <li>6.生成记录（生成编号，生成时间，更新时间，生成状态，生成资料，操作）<br>(1)查看记录：查看用户生成的订单的各种信息。例如生成时间，更新时间，生成状态，反馈内容，下载文件，上传文件等，以及
                                    生成状态的筛选<br>(2)反馈功能：用户可对订单进行反馈，包括反馈内容，回传图纸（上传dxf文件），不合理项勾选，截图反馈（可上传多个截图，放大看细节或删除）,提交成功和失败均有提示<br>(3)预览功能：在不同预览状态点击预览模式可跳转至生成模块对应的状态流程
                                </li>
                                <li>7.4.18，4.19，4.22，5.20，5.27上线版本反馈优化</li>
                            </ul>
                            <ul>
                                技术亮点:
                                <li>1.基于flex布局重构和优化项目总体样式</li>
                                <li>2.使用websocket实现ai沟通对话生成需求</li>
                                <li>3.使用sessionStorage来存储用户token和角色，姓名等信息，以及ai自动上传，预览模式所需要的兄弟组件传值</li>
                                <li>4.使用element UI组件库快速实现生成记录和用户管理</li>
                                <li>5.请求拦截器为每个接口加上token请求头，响应拦截器根据后端返的code来进行相应token失效/过期处理</li>
                                <li>6.测试环境和正式环境的配置。注：只有打包后版本才会切正式环境，其余皆为测试环境</li>
                                <li>7.使用live server来预览正式上线版本的项目</li>
                            </ul>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="flex flex-col">
                <div class="flex flex-col">
                    <div class="my-4 w-full h-10 bg-gray-200 bg-opacity-50 border-l-4 flex justify-start items-center"
                        :class="borderClasses">
                        <h2 class="font-semibold text-xl ml-4">教育经历</h2>
                    </div>
                    <div >
                        <ul class="list-none list-inside flex flex-wrap justify-between leading-loose min-w-full">
                            <li class="flex flex-none mr-8 ">
                                <h3 class="text-lg font-semibold inline-block">南开大学滨海学院</h3>
                                <span class="text-center min-w-10 ml-5">本科</span>
                               <span class="ml-5">计算机科学与技术</span>
                            </li>
                            <li class="text-right">2019-2023</li>
                        </ul>
                        <ul class="list-none list-outside ">
                            <li>
                                主修课程：数据结构，计算机网络，操作系统，计算机组成原理，数据库原理，java,python，HTML5程序设计，大数据分析与处理，web可视化工程，软件测试等
                            </li>
                            <li>
                                在校期间担任班级心理委员，帮助班里同学疏解心理问题
                            </li>
                            <li>
                                在校期间担任大数据，软件测试，python程序设计的课程小组组长，带领组员完成期末项目并取得高分
                            </li>
                            <li>
                                在校期间有过计算机考研经历，科目为数据结构和计算机网络且已过国家线
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="flex flex-col">
                <div class="flex flex-col">
                    <div class="my-4 w-full h-10 bg-gray-200 bg-opacity-50 border-l-4 flex justify-start items-center"
                        :class="borderClasses">
                        <h2 class="font-semibold text-xl ml-4">资格证书</h2>
                    </div>
                    <div>
                        <ul class="list-none list-inside flex flex-wrap justify-start leading-loose">
                            <li>大学英语四级</li>
                            <li class="ml-10">大学英语六级</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="flex flex-col">
                <div class="flex flex-col">
                    <div class="my-4 w-full h-10 bg-gray-200 bg-opacity-50 border-l-4 flex justify-start items-center"
                        :class="borderClasses">
                        <h2 class="font-semibold text-xl ml-4">社交主页</h2>
                    </div>
                    <div>
                        https://github.com/yanzi113
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script setup>
import { ref, computed } from "vue";
// 创建一个响应式变量存储当前主题状态
const isDarkMode = ref(false);
// 切换主题的函数
const toggleTheme = () => {
    isDarkMode.value = !isDarkMode.value;
}
// 根据当前主题状态返回对应的Tailwind CSS类名
const themeClasses = computed(() => ({
    // 默认的Tailwind CSS类名
    'bg-white': !isDarkMode.value,
    'text-black': !isDarkMode.value,
    // Dark mode时的Tailwind CSS类名
    'bg-gray-900': isDarkMode.value,
    'text-white': isDarkMode.value,
}))
const borderClasses = computed(() => ({
    // 默认的Tailwind CSS类名
    'border-black': !isDarkMode.value,
    // Dark mode时的Tailwind CSS类名
    'border-white': isDarkMode.value,
}))
</script>
<style>
/* ol li {
    list-style-type: decimal !important;
    list-style-position: inside !important;

} */
/* body {
    @apply bg-white text-gray-900
} */
</style>