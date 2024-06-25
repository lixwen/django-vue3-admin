<template>

    <div id="base">

        <div id="u1" class="ax_default" data-left="0" data-top="2846" data-width="100%" data-height="372"
            layer-opacity="1">

            <div id="u2" class="ax_default">
                <div id="u2_state0" class="panel_state" data-label="State1" style="">
                    <div id="u2_state0_content" class="panel_state_content">
                    </div>
                </div>
            </div>

            <div id="u3" class="ax_default label">
                <div id="u3_div" class=""></div>
                <div id="u3_text" class="text ">
                    <p><span>联系我们</span></p>
                </div>
            </div>

            <div id="u4" class="ax_default label">
                <div id="u4_div" class=""></div>
                <div id="u4_text" class="text ">
                    <p><span>关于AI助手</span></p>
                </div>
            </div>

            <div id="u5" class="ax_default label">
                <div id="u5_div" class=""></div>
                <div id="u5_text" class="text ">
                    <p><span>热门产品</span></p>
                </div>
            </div>

            <div id="u6" class="ax_default label">
                <div id="u6_div" class=""></div>
                <div id="u6_text" class="text ">
                    <p><span>支持与服务</span></p>
                </div>
            </div>

            <div id="u7" class="ax_default label">
                <div id="u7_div" class=""></div>
                <div id="u7_text" class="text ">
                    <p><span>AI助手简介</span></p>
                </div>
            </div>

            <div id="u8" class="ax_default label">
                <div id="u8_div" class=""></div>
                <div id="u8_text" class="text ">
                    <p><span>新闻资讯</span></p>
                </div>
            </div>

            <div id="u9" class="ax_default label">
                <div id="u9_div" class=""></div>
                <div id="u9_text" class="text ">
                    <p><span>使用文档</span></p>
                </div>
            </div>

            <div id="u10" class="ax_default label">
                <div id="u10_div" class=""></div>
                <div id="u10_text" class="text ">
                    <p><span>需求登记</span></p>
                </div>
            </div>

            <div id="u11" class="ax_default line">
                <img id="u11_img" class="img " src="../../assets/img/home/u11.svg" />
                <div id="u11_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>

            <div id="u12" class="ax_default label">
                <div id="u12_div" class=""></div>
                <div id="u12_text" class="text ">
                    <p><span>© 2024, 南京云铎科技邮箱公司。保留一切权利。</span></p>
                </div>
            </div>

            <div id="u13" class="ax_default line">
                <img id="u13_img" class="img " src="../../assets/img/home/u13.svg" />
                <div id="u13_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>

            <div id="u14" class="ax_default label">
                <div id="u14_div" class=""></div>
                <div id="u14_text" class="text ">
                    <p><span>联系方式：</span></p>
                    <p><span>QQ：284781293</span></p>
                </div>
            </div>
        </div>
        <div id="u0" style="display:none; visibility:hidden;"></div>

        <!-- 轮播 (Dynamic Panel) -->
        <div id="u15" class="ax_default" data-label="轮播">
            <div v-show="currentState === 0" id="u15_state0" class="panel_state" data-label="1">
                <div id="u15_state0_content" class="panel_state_content">
                    <div id="u16" class="ax_default" data-left="40" data-top="60" data-width="1200" data-height="248"
                        layer-opacity="1">
                        <div id="u17" class="ax_default label">
                            <div id="u17_div" class=""></div>
                            <div id="u17_text" class="text ">
                                <p><span>江苏设计院解决方案AI助手</span></p>
                            </div>
                        </div>
                        <div id="u18" class="ax_default label">
                            <div id="u18_div" class=""></div>
                            <div id="u18_text" class="text ">
                                <p><span>重磅上线！</span></p>
                            </div>
                        </div>
                        <div id="u19" class="ax_default label">
                            <img id="u19_img" class="img" src="../../assets/img/home/u19.svg" />
                            <div id="u19_text" class="text ">
                                <p><span>了解详情</span></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div v-show="currentState === 1" id="u15_state1" class="panel_state" data-label="2">
                <div id="u15_state1_content" class="panel_state_content">
                    <div id="u20" class="ax_default" data-left="40" data-top="60" data-width="1200" data-height="248"
                        layer-opacity="1">
                        <div id="u21" class="ax_default label">
                            <div id="u21_div" class=""></div>
                            <div id="u21_text" class="text ">
                                <p><span>匹配最符合客户需求的方案</span></p>
                            </div>
                        </div>
                        <div id="u22" class="ax_default label">
                            <div id="u22_div" class=""></div>
                            <div id="u22_text" class="text ">
                                <p><span>客户经理专注客情关系，让AI帮您寻找最符合要求的方案</span></p>
                            </div>
                        </div>
                        <div id="u23" class="ax_default label">
                            <img id="u23_img" class="img" src="../../assets/img/home/u19.svg" />
                            <div id="u23_text" class="text ">
                                <p><span>了解详情</span></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div v-show="currentState === 2" id="u15_state2" class="panel_state" data-label="3">
                <div id="u15_state2_content" class="panel_state_content">
                    <div id="u24" class="ax_default" data-left="40" data-top="60" data-width="1200" data-height="248"
                        layer-opacity="1">
                        <div id="u25" class="ax_default label">
                            <div id="u25_div" class=""></div>
                            <div id="u25_text" class="text ">
                                <p><span>针对方案进行全方位咨询</span></p>
                            </div>
                        </div>
                        <div id="u26" class="ax_default label">
                            <div id="u26_div" class=""></div>
                            <div id="u26_text" class="text ">
                                <p><span>不再担心方案咨询回复不及时，像聊天一样向AI提问</span></p>
                            </div>
                        </div>
                        <div id="u27" class="ax_default label">
                            <img id="u27_img" class="img" src="../../assets/img/home/u19.svg" />
                            <div id="u27_text" class="text ">
                                <p><span>了解详情</span></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div v-show="currentState === 3" id="u15_state3" class="panel_state" data-label="4">
                <div id="u15_state3_content" class="panel_state_content">
                    <div id="u28" class="ax_default" data-left="40" data-top="60" data-width="1200" data-height="248"
                        layer-opacity="1">
                        <div id="u29" class="ax_default label">
                            <div id="u29_div" class=""></div>
                            <div id="u29_text" class="text ">
                                <p><span>知识库不断迭代更新中</span></p>
                            </div>
                        </div>
                        <div id="u30" class="ax_default label">
                            <div id="u30_div" class=""></div>
                            <div id="u30_text" class="text ">
                                <p><span>内置江苏设计院精选行业标杆解决方案，内容不断更新升级</span></p>
                            </div>
                        </div>
                        <div id="u31" class="ax_default label">
                            <img id="u31_img" class="img" src="../../assets/img/home/u19.svg" />
                            <div id="u31_text" class="text ">
                                <p><span>了解详情</span></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Unnamed (Dynamic Panel) -->
        <div id="u32" class="ax_default">
            <div id="u32_state0" class="panel_state" data-label="State1" style="">
                <div id="u32_state0_content" class="panel_state_content">
                </div>
            </div>
        </div>

        <!-- Unnamed (Rectangle) -->
        <div id="u34" class="ax_default label">
            <div id="u34_div" class=""></div>
            <div id="u34_text" class="text ">
                <p><span>用AI，加速知识的流通</span></p>
            </div>
        </div>

        <div id="u35" class="ax_default">
            <div id="u35_state0" class="panel_state" data-label="State1" style="">
                <div id="u35_state0_content" class="panel_state_content">

                    <!-- Unnamed (Repeater) -->
                    <div id="u36" class="ax_default">
                        <!-- <script id="u36_script" type="axure-repeater-template">
                        </script> -->
                        <div id="u36-1" class="" style="width: 366px; height: 294px;">

                            <!-- Unnamed (Group) -->
                            <div id="u37-1" class="ax_default u37" style="visibility: inherit" data-left="0"
                                data-top="0" data-width="366" data-height="294" layer-opacity="1">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u38-1" class="ax_default box_2 u38"
                                    style="width: 366px; height: 294px; left: 0px; top: 0px;visibility: inherit">
                                    <div id="u38-1_div" class="u38_div"
                                        style="width: 366px; height: 294px;visibility: inherit"></div>
                                    <div id="u38-1_text" class="text u38_text" style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u39-1" class="ax_default u39" style="visibility: inherit" data-left="0"
                                    data-top="75" data-width="366" data-height="144" layer-opacity="1">

                                    <!-- a0 (Image) -->
                                    <div id="u40-1" class="ax_default image u40" data-label="a0"
                                        style="width: 64px; height: 64px; left: 151px; top: 75px;visibility: inherit">
                                        <img id="u40-1_img" class="img u40_img"
                                            src="../../assets/img/home/a0_u40.png" />
                                        <div id="u40-1_text" class="text u40_text"
                                            style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- a1 (Rectangle) -->
                                    <div id="u41-1" class="ax_default label u41" data-label="a1"
                                        style="width: 366px; height: 24px; left: 0px; top: 167px;visibility: inherit">
                                        <div id="u41-1_div" class="u41_div"
                                            style="width: 366px; height: 24px;visibility: inherit"></div>
                                        <div id="u41-1_text" class="text u41_text" style="visibility: inherit">
                                            <p><span>弹性云服务器 ECS</span></p>
                                        </div>
                                    </div>

                                    <!-- a2 (Rectangle) -->
                                    <div id="u42-1" class="ax_default label u42" data-label="a2"
                                        style="width: 366px; height: 20px; left: 0px; top: 199px;visibility: inherit">
                                        <div id="u42-1_div" class="u42_div"
                                            style="width: 366px; height: 20px;visibility: inherit"></div>
                                        <div id="u42-1_text" class="text u42_text" style="visibility: inherit">
                                            <p><span>可随时自动获取、弹性伸缩的云服务器</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u36-2" class="" style="width: 366px; height: 294px;">

                            <!-- Unnamed (Group) -->
                            <div id="u37-2" class="ax_default u37" style="visibility: inherit" data-left="0"
                                data-top="0" data-width="366" data-height="294" layer-opacity="1">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u38-2" class="ax_default box_2 u38"
                                    style="width: 366px; height: 294px; left: 0px; top: 0px;visibility: inherit">
                                    <div id="u38-2_div" class="u38_div"
                                        style="width: 366px; height: 294px;visibility: inherit"></div>
                                    <div id="u38-2_text" class="text u38_text" style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u39-2" class="ax_default u39" style="visibility: inherit" data-left="0"
                                    data-top="75" data-width="366" data-height="144" layer-opacity="1">

                                    <!-- a0 (Image) -->
                                    <div id="u40-2" class="ax_default image u40" data-label="a0"
                                        style="width: 64px; height: 64px; left: 151px; top: 75px;visibility: inherit">
                                        <img id="u40-2_img" class="img u40_img"
                                            src="../../assets/img/home/a0_u40.png" />
                                        <div id="u40-2_text" class="text u40_text"
                                            style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- a1 (Rectangle) -->
                                    <div id="u41-2" class="ax_default label u41" data-label="a1"
                                        style="width: 366px; height: 24px; left: 0px; top: 167px;visibility: inherit">
                                        <div id="u41-2_div" class="u41_div"
                                            style="width: 366px; height: 24px;visibility: inherit"></div>
                                        <div id="u41-2_text" class="text u41_text" style="visibility: inherit">
                                            <p><span>弹性云服务器 ECS</span></p>
                                        </div>
                                    </div>

                                    <!-- a2 (Rectangle) -->
                                    <div id="u42-2" class="ax_default label u42" data-label="a2"
                                        style="width: 366px; height: 20px; left: 0px; top: 199px;visibility: inherit">
                                        <div id="u42-2_div" class="u42_div"
                                            style="width: 366px; height: 20px;visibility: inherit"></div>
                                        <div id="u42-2_text" class="text u42_text" style="visibility: inherit">
                                            <p><span>可随时自动获取、弹性伸缩的云服务器</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u36-3" class="" style="width: 366px; height: 294px;">

                            <!-- Unnamed (Group) -->
                            <div id="u37-3" class="ax_default u37" style="visibility: inherit" data-left="0"
                                data-top="0" data-width="366" data-height="294" layer-opacity="1">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u38-3" class="ax_default box_2 u38"
                                    style="width: 366px; height: 294px; left: 0px; top: 0px;visibility: inherit">
                                    <div id="u38-3_div" class="u38_div"
                                        style="width: 366px; height: 294px;visibility: inherit"></div>
                                    <div id="u38-3_text" class="text u38_text" style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u39-3" class="ax_default u39" style="visibility: inherit" data-left="0"
                                    data-top="75" data-width="366" data-height="144" layer-opacity="1">

                                    <!-- a0 (Image) -->
                                    <div id="u40-3" class="ax_default image u40" data-label="a0"
                                        style="width: 64px; height: 64px; left: 151px; top: 75px;visibility: inherit">
                                        <img id="u40-3_img" class="img u40_img"
                                            src="../../assets/img/home/a0_u40.png" />
                                        <div id="u40-3_text" class="text u40_text"
                                            style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- a1 (Rectangle) -->
                                    <div id="u41-3" class="ax_default label u41" data-label="a1"
                                        style="width: 366px; height: 24px; left: 0px; top: 167px;visibility: inherit">
                                        <div id="u41-3_div" class="u41_div"
                                            style="width: 366px; height: 24px;visibility: inherit"></div>
                                        <div id="u41-3_text" class="text u41_text" style="visibility: inherit">
                                            <p><span>弹性云服务器 ECS</span></p>
                                        </div>
                                    </div>

                                    <!-- a2 (Rectangle) -->
                                    <div id="u42-3" class="ax_default label u42" data-label="a2"
                                        style="width: 366px; height: 20px; left: 0px; top: 199px;visibility: inherit">
                                        <div id="u42-3_div" class="u42_div"
                                            style="width: 366px; height: 20px;visibility: inherit"></div>
                                        <div id="u42-3_text" class="text u42_text" style="visibility: inherit">
                                            <p><span>可随时自动获取、弹性伸缩的云服务器</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u36-4" class="" style="width: 366px; height: 294px;">

                            <!-- Unnamed (Group) -->
                            <div id="u37-4" class="ax_default u37" style="visibility: inherit" data-left="0"
                                data-top="0" data-width="366" data-height="294" layer-opacity="1">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u38-4" class="ax_default box_2 u38"
                                    style="width: 366px; height: 294px; left: 0px; top: 0px;visibility: inherit">
                                    <div id="u38-4_div" class="u38_div"
                                        style="width: 366px; height: 294px;visibility: inherit"></div>
                                    <div id="u38-4_text" class="text u38_text" style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u39-4" class="ax_default u39" style="visibility: inherit" data-left="0"
                                    data-top="75" data-width="366" data-height="144" layer-opacity="1">

                                    <!-- a0 (Image) -->
                                    <div id="u40-4" class="ax_default image u40" data-label="a0"
                                        style="width: 64px; height: 64px; left: 151px; top: 75px;visibility: inherit">
                                        <img id="u40-4_img" class="img u40_img"
                                            src="../../assets/img/home/a0_u40.png" />
                                        <div id="u40-4_text" class="text u40_text"
                                            style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- a1 (Rectangle) -->
                                    <div id="u41-4" class="ax_default label u41" data-label="a1"
                                        style="width: 366px; height: 24px; left: 0px; top: 167px;visibility: inherit">
                                        <div id="u41-4_div" class="u41_div"
                                            style="width: 366px; height: 24px;visibility: inherit"></div>
                                        <div id="u41-4_text" class="text u41_text" style="visibility: inherit">
                                            <p><span>弹性云服务器 ECS</span></p>
                                        </div>
                                    </div>

                                    <!-- a2 (Rectangle) -->
                                    <div id="u42-4" class="ax_default label u42" data-label="a2"
                                        style="width: 366px; height: 20px; left: 0px; top: 199px;visibility: inherit">
                                        <div id="u42-4_div" class="u42_div"
                                            style="width: 366px; height: 20px;visibility: inherit"></div>
                                        <div id="u42-4_text" class="text u42_text" style="visibility: inherit">
                                            <p><span>可随时自动获取、弹性伸缩的云服务器</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u36-5" class="" style="width: 366px; height: 294px;">

                            <!-- Unnamed (Group) -->
                            <div id="u37-5" class="ax_default u37" style="visibility: inherit" data-left="0"
                                data-top="0" data-width="366" data-height="294" layer-opacity="1">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u38-5" class="ax_default box_2 u38"
                                    style="width: 366px; height: 294px; left: 0px; top: 0px;visibility: inherit">
                                    <div id="u38-5_div" class="u38_div"
                                        style="width: 366px; height: 294px;visibility: inherit"></div>
                                    <div id="u38-5_text" class="text u38_text" style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u39-5" class="ax_default u39" style="visibility: inherit" data-left="0"
                                    data-top="75" data-width="366" data-height="144" layer-opacity="1">

                                    <!-- a0 (Image) -->
                                    <div id="u40-5" class="ax_default image u40" data-label="a0"
                                        style="width: 64px; height: 64px; left: 151px; top: 75px;visibility: inherit">
                                        <img id="u40-5_img" class="img u40_img"
                                            src="../../assets/img/home/a0_u40.png" />
                                        <div id="u40-5_text" class="text u40_text"
                                            style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- a1 (Rectangle) -->
                                    <div id="u41-5" class="ax_default label u41" data-label="a1"
                                        style="width: 366px; height: 24px; left: 0px; top: 167px;visibility: inherit">
                                        <div id="u41-5_div" class="u41_div"
                                            style="width: 366px; height: 24px;visibility: inherit"></div>
                                        <div id="u41-5_text" class="text u41_text" style="visibility: inherit">
                                            <p><span>弹性云服务器 ECS</span></p>
                                        </div>
                                    </div>

                                    <!-- a2 (Rectangle) -->
                                    <div id="u42-5" class="ax_default label u42" data-label="a2"
                                        style="width: 366px; height: 20px; left: 0px; top: 199px;visibility: inherit">
                                        <div id="u42-5_div" class="u42_div"
                                            style="width: 366px; height: 20px;visibility: inherit"></div>
                                        <div id="u42-5_text" class="text u42_text" style="visibility: inherit">
                                            <p><span>可随时自动获取、弹性伸缩的云服务器</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u36-6" class="" style="width: 366px; height: 294px;">

                            <!-- Unnamed (Group) -->
                            <div id="u37-6" class="ax_default u37" style="visibility: inherit" data-left="0"
                                data-top="0" data-width="366" data-height="294" layer-opacity="1">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u38-6" class="ax_default box_2 u38"
                                    style="width: 366px; height: 294px; left: 0px; top: 0px;visibility: inherit">
                                    <div id="u38-6_div" class="u38_div"
                                        style="width: 366px; height: 294px;visibility: inherit"></div>
                                    <div id="u38-6_text" class="text u38_text" style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u39-6" class="ax_default u39" style="visibility: inherit" data-left="0"
                                    data-top="75" data-width="366" data-height="144" layer-opacity="1">

                                    <!-- a0 (Image) -->
                                    <div id="u40-6" class="ax_default image u40" data-label="a0"
                                        style="width: 64px; height: 64px; left: 151px; top: 75px;visibility: inherit">
                                        <img id="u40-6_img" class="img u40_img"
                                            src="../../assets/img/home/a0_u40.png" />
                                        <div id="u40-6_text" class="text u40_text"
                                            style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- a1 (Rectangle) -->
                                    <div id="u41-6" class="ax_default label u41" data-label="a1"
                                        style="width: 366px; height: 24px; left: 0px; top: 167px;visibility: inherit">
                                        <div id="u41-6_div" class="u41_div"
                                            style="width: 366px; height: 24px;visibility: inherit"></div>
                                        <div id="u41-6_text" class="text u41_text" style="visibility: inherit">
                                            <p><span>弹性云服务器 ECS</span></p>
                                        </div>
                                    </div>

                                    <!-- a2 (Rectangle) -->
                                    <div id="u42-6" class="ax_default label u42" data-label="a2"
                                        style="width: 366px; height: 20px; left: 0px; top: 199px;visibility: inherit">
                                        <div id="u42-6_div" class="u42_div"
                                            style="width: 366px; height: 20px;visibility: inherit"></div>
                                        <div id="u42-6_text" class="text u42_text" style="visibility: inherit">
                                            <p><span>可随时自动获取、弹性伸缩的云服务器</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u36-7" class="" style="width: 366px; height: 294px;">

                            <!-- Unnamed (Group) -->
                            <div id="u37-7" class="ax_default u37" style="visibility: inherit" data-left="0"
                                data-top="0" data-width="366" data-height="294" layer-opacity="1">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u38-7" class="ax_default box_2 u38"
                                    style="width: 366px; height: 294px; left: 0px; top: 0px;visibility: inherit">
                                    <div id="u38-7_div" class="u38_div"
                                        style="width: 366px; height: 294px;visibility: inherit"></div>
                                    <div id="u38-7_text" class="text u38_text" style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u39-7" class="ax_default u39" style="visibility: inherit" data-left="0"
                                    data-top="75" data-width="366" data-height="144" layer-opacity="1">

                                    <!-- a0 (Image) -->
                                    <div id="u40-7" class="ax_default image u40" data-label="a0"
                                        style="width: 64px; height: 64px; left: 151px; top: 75px;visibility: inherit">
                                        <img id="u40-7_img" class="img u40_img"
                                            src="../../assets/img/home/a0_u40.png" />
                                        <div id="u40-7_text" class="text u40_text"
                                            style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- a1 (Rectangle) -->
                                    <div id="u41-7" class="ax_default label u41" data-label="a1"
                                        style="width: 366px; height: 24px; left: 0px; top: 167px;visibility: inherit">
                                        <div id="u41-7_div" class="u41_div"
                                            style="width: 366px; height: 24px;visibility: inherit"></div>
                                        <div id="u41-7_text" class="text u41_text" style="visibility: inherit">
                                            <p><span>弹性云服务器 ECS</span></p>
                                        </div>
                                    </div>

                                    <!-- a2 (Rectangle) -->
                                    <div id="u42-7" class="ax_default label u42" data-label="a2"
                                        style="width: 366px; height: 20px; left: 0px; top: 199px;visibility: inherit">
                                        <div id="u42-7_div" class="u42_div"
                                            style="width: 366px; height: 20px;visibility: inherit"></div>
                                        <div id="u42-7_text" class="text u42_text" style="visibility: inherit">
                                            <p><span>可随时自动获取、弹性伸缩的云服务器</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u36-8" class="" style="width: 366px; height: 294px;">

                            <!-- Unnamed (Group) -->
                            <div id="u37-8" class="ax_default u37" style="visibility: inherit" data-left="0"
                                data-top="0" data-width="366" data-height="294" layer-opacity="1">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u38-8" class="ax_default box_2 u38"
                                    style="width: 366px; height: 294px; left: 0px; top: 0px;visibility: inherit">
                                    <div id="u38-8_div" class="u38_div"
                                        style="width: 366px; height: 294px;visibility: inherit"></div>
                                    <div id="u38-8_text" class="text u38_text" style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u39-8" class="ax_default u39" style="visibility: inherit" data-left="0"
                                    data-top="75" data-width="366" data-height="144" layer-opacity="1">

                                    <!-- a0 (Image) -->
                                    <div id="u40-8" class="ax_default image u40" data-label="a0"
                                        style="width: 64px; height: 64px; left: 151px; top: 75px;visibility: inherit">
                                        <img id="u40-8_img" class="img u40_img"
                                            src="../../assets/img/home/a0_u40.png" />
                                        <div id="u40-8_text" class="text u40_text"
                                            style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- a1 (Rectangle) -->
                                    <div id="u41-8" class="ax_default label u41" data-label="a1"
                                        style="width: 366px; height: 24px; left: 0px; top: 167px;visibility: inherit">
                                        <div id="u41-8_div" class="u41_div"
                                            style="width: 366px; height: 24px;visibility: inherit"></div>
                                        <div id="u41-8_text" class="text u41_text" style="visibility: inherit">
                                            <p><span>弹性云服务器 ECS</span></p>
                                        </div>
                                    </div>

                                    <!-- a2 (Rectangle) -->
                                    <div id="u42-8" class="ax_default label u42" data-label="a2"
                                        style="width: 366px; height: 20px; left: 0px; top: 199px;visibility: inherit">
                                        <div id="u42-8_div" class="u42_div"
                                            style="width: 366px; height: 20px;visibility: inherit"></div>
                                        <div id="u42-8_text" class="text u42_text" style="visibility: inherit">
                                            <p><span>可随时自动获取、弹性伸缩的云服务器</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Unnamed (Rectangle) -->
        <div id="u50" class="ax_default label">
            <div id="u50_div" class=""></div>
            <div id="u50_text" class="text ">
                <p><span>市场热点解决方案推荐</span></p>
            </div>
        </div>


        <!-- Unnamed (Group) -->
        <div id="u69" class="ax_default" data-left="0" data-top="618" data-width="1680" data-height="104"
            layer-opacity="1">

            <!-- Unnamed (Dynamic Panel) -->
            <div id="u70" class="ax_default">
                <div id="u70_state0" class="panel_state" data-label="State1" style="">
                    <div id="u70_state0_content" class="panel_state_content">
                    </div>
                </div>
            </div>

            <!-- Unnamed (Group) -->
            <div id="u71" class="ax_default" data-left="1218" data-top="618" data-width="378" data-height="104"
                layer-opacity="1">

                <!-- Unnamed (Rectangle) -->
                <div id="u72" class="ax_default box_2">
                    <div id="u72_div" class=""></div>
                    <div id="u72_text" class="text " style="display:none; visibility: hidden">
                        <p></p>
                    </div>
                </div>

                <!-- Unnamed (Rectangle) -->
                <div id="u73" class="ax_default label">
                    <div id="u73_div" class=""></div>
                    <div id="u73_text" class="text ">
                        <p><span>&nbsp;一切皆服务</span></p>
                    </div>
                </div>

                <!-- Unnamed (Rectangle) -->
                <div id="u74" class="ax_default label">
                    <div id="u74_div" class=""></div>
                    <div id="u74_text" class="text ">
                        <p><span>查方案、学方案、联系售前支撑</span></p>
                    </div>
                </div>
            </div>

            <!-- Unnamed (Group) -->
            <div id="u75" class="ax_default" data-left="84" data-top="618" data-width="378" data-height="104"
                layer-opacity="1">

                <!-- Unnamed (Rectangle) -->
                <div id="u76" class="ax_default box_2">
                    <div id="u76_div" class=""></div>
                    <div id="u76_text" class="text " style="display:none; visibility: hidden">
                        <p></p>
                    </div>
                </div>

                <!-- Unnamed (Group) -->
                <div id="u77" class="ax_default" data-left="84" data-top="642" data-width="378" data-height="54"
                    layer-opacity="1">

                    <!-- Unnamed (Rectangle) -->
                    <div id="u78" class="ax_default label">
                        <div id="u78_div" class=""></div>
                        <div id="u78_text" class="text ">
                            <p><span>AI匹配客户需求</span></p>
                        </div>
                    </div>

                    <!-- Unnamed (Rectangle) -->
                    <div id="u79" class="ax_default label">
                        <div id="u79_div" class=""></div>
                        <div id="u79_text" class="text ">
                            <p><span>输入客户需求，寻找最佳方案</span></p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Unnamed (Group) -->
            <div id="u80" class="ax_default" data-left="462" data-top="618" data-width="378" data-height="104"
                layer-opacity="1">

                <!-- Unnamed (Rectangle) -->
                <div id="u81" class="ax_default box_2">
                    <div id="u81_div" class=""></div>
                    <div id="u81_text" class="text " style="display:none; visibility: hidden">
                        <p></p>
                    </div>
                </div>

                <!-- Unnamed (Group) -->
                <div id="u82" class="ax_default" data-left="462" data-top="642" data-width="378" data-height="54"
                    layer-opacity="1">

                    <!-- Unnamed (Rectangle) -->
                    <div id="u83" class="ax_default label">
                        <div id="u83_div" class=""></div>
                        <div id="u83_text" class="text ">
                            <p><span>查阅行业解决方案</span></p>
                        </div>
                    </div>

                    <!-- Unnamed (Rectangle) -->
                    <div id="u84" class="ax_default label">
                        <div id="u84_div" class=""></div>
                        <div id="u84_text" class="text ">
                            <p><span>300+江苏设计院精选方案</span></p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Unnamed (Group) -->
            <div id="u85" class="ax_default" data-left="840" data-top="618" data-width="378" data-height="104"
                layer-opacity="1">

                <!-- Unnamed (Rectangle) -->
                <div id="u86" class="ax_default box_2">
                    <div id="u86_div" class=""></div>
                    <div id="u86_text" class="text " style="display:none; visibility: hidden">
                        <p></p>
                    </div>
                </div>

                <!-- Unnamed (Rectangle) -->
                <div id="u87" class="ax_default label">
                    <div id="u87_div" class=""></div>
                    <div id="u87_text" class="text ">
                        <p><span>AI咨询与问答</span></p>
                    </div>
                </div>

                <!-- Unnamed (Rectangle) -->
                <div id="u88" class="ax_default label">
                    <div id="u88_div" class=""></div>
                    <div id="u88_text" class="text ">
                        <p><span>方案总结提炼、内容咨询</span></p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Unnamed (Group) -->
        <div id="u89" class="ax_default" data-left="767" data-top="1526" data-width="163" data-height="28"
            layer-opacity="1">

            <!-- Unnamed (Rectangle) -->
            <div id="u90" class="ax_default label">
                <div id="u90_div" class=""></div>
                <div id="u90_text" class="text ">
                    <p><span>查看所有解决方案</span></p>
                </div>
            </div>

            <!-- Unnamed (Shape) -->
            <div id="u91" class="ax_default box_21">
                <img id="u91_img" class="img " src="../../assets/img/home/u91.svg" />
                <div id="u91_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>
        </div>

        <!-- Unnamed (Dynamic Panel) -->
        <div id="u92" class="ax_default">
            <div id="u92_state0" class="panel_state" data-label="State1" style="">
                <div id="u92_state0_content" class="panel_state_content">

                    <!-- Unnamed (Group) -->
                    <div id="u93" class="ax_default" data-left="266" data-top="0" data-width="1172" data-height="560"
                        layer-opacity="1">

                        <!-- Unnamed (Image) -->
                        <div id="u94" class="ax_default image">
                            <img id="u94_img" class="img " src="../../assets/img/home/u94.svg" />
                            <div id="u94_text" class="text " style="display:none; visibility: hidden">
                                <p></p>
                            </div>
                        </div>

                        <!-- Unnamed (Rectangle) -->
                        <div id="u95" class="ax_default box_2">
                            <img id="u95_img" class="img " src="../../assets/img/home/u95.svg" />
                            <div id="u95_text" class="text " style="display:none; visibility: hidden">
                                <p></p>
                            </div>
                        </div>

                        <!-- Unnamed (Group) -->
                        <div id="u96" class="ax_default" data-left="346" data-top="221" data-width="380"
                            data-height="167" layer-opacity="1">

                            <!-- Unnamed (Rectangle) -->
                            <div id="u97" class="ax_default label">
                                <div id="u97_div" class=""></div>
                                <div id="u97_text" class="text ">
                                    <p><span>电商</span></p>
                                </div>
                            </div>

                            <!-- Unnamed (Rectangle) -->
                            <div id="u98" class="ax_default label">
                                <div id="u98_div" class=""></div>
                                <div id="u98_text" class="text ">
                                    <p><span>艾斯云提供丰富的行业平台服务和基础云服务，打造端到端电商解决方案，助力企业构建自有电商生态</span></p>
                                </div>
                            </div>

                            <!-- Unnamed (Rectangle) -->
                            <div id="u99" class="ax_default label">
                                <img id="u99_img" class="img " src="../../assets/img/home/u99.svg" />
                                <div id="u99_text" class="text ">
                                    <p><span>了解更多</span></p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Unnamed (Group) -->
                    <div id="u100" class="ax_default" data-left="1462" data-top="0" data-width="1172" data-height="560"
                        layer-opacity="1">

                        <!-- Unnamed (Image) -->
                        <div id="u101" class="ax_default image">
                            <img id="u101_img" class="img " src="../../assets/img/home/u101.svg" />
                            <div id="u101_text" class="text " style="display:none; visibility: hidden">
                                <p></p>
                            </div>
                        </div>

                        <!-- Unnamed (Rectangle) -->
                        <div id="u102" class="ax_default box_2">
                            <img id="u102_img" class="img " src="../../assets/img/home/u95.svg" />
                            <div id="u102_text" class="text " style="display:none; visibility: hidden">
                                <p></p>
                            </div>
                        </div>

                        <!-- Unnamed (Group) -->
                        <div id="u103" class="ax_default" data-left="1542" data-top="221" data-width="380"
                            data-height="167" layer-opacity="1">

                            <!-- Unnamed (Rectangle) -->
                            <div id="u104" class="ax_default label">
                                <img id="u104_img" class="img " src="../../assets/img/home/u99.svg" />
                                <div id="u104_text" class="text ">
                                    <p><span>了解更多</span></p>
                                </div>
                            </div>

                            <!-- Unnamed (Rectangle) -->
                            <div id="u105" class="ax_default label">
                                <div id="u105_div" class=""></div>
                                <div id="u105_text" class="text ">
                                    <p><span>汽车</span></p>
                                </div>
                            </div>

                            <!-- Unnamed (Rectangle) -->
                            <div id="u106" class="ax_default label">
                                <div id="u106_div" class=""></div>
                                <div id="u106_text" class="text ">
                                    <p><span>快速构建保险全业务系统，提供基于合规、安全、可靠的金融专区，专属云等多种部署方式，助力险企实现数字化转型</span></p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Unnamed (Group) -->
                    <div id="u107" class="ax_default" data-left="-930" data-top="0" data-width="1172" data-height="560"
                        layer-opacity="1">

                        <!-- Unnamed (Image) -->
                        <div id="u108" class="ax_default image">
                            <img id="u108_img" class="img " src="../../assets/img/home/u108.svg" />
                            <div id="u108_text" class="text " style="display:none; visibility: hidden">
                                <p></p>
                            </div>
                        </div>

                        <!-- Unnamed (Rectangle) -->
                        <div id="u109" class="ax_default box_2">
                            <img id="u109_img" class="img " src="../../assets/img/home/u95.svg" />
                            <div id="u109_text" class="text " style="display:none; visibility: hidden">
                                <p></p>
                            </div>
                        </div>

                        <!-- Unnamed (Group) -->
                        <div id="u110" class="ax_default" data-left="-850" data-top="221" data-width="380"
                            data-height="167" layer-opacity="1">

                            <!-- Unnamed (Rectangle) -->
                            <div id="u111" class="ax_default label">
                                <div id="u111_div" class=""></div>
                                <div id="u111_text" class="text ">
                                    <p><span>城市智能体</span></p>
                                </div>
                            </div>

                            <!-- Unnamed (Rectangle) -->
                            <div id="u112" class="ax_default label">
                                <div id="u112_div" class=""></div>
                                <div id="u112_text" class="text ">
                                    <p><span>聚焦政务与城市数字化，面向场景进行流程再造与优化，真正提升人民的获得感、幸福感和安全感</span></p>
                                </div>
                            </div>

                            <!-- Unnamed (Rectangle) -->
                            <div id="u113" class="ax_default label">
                                <img id="u113_img" class="img " src="../../assets/img/home/u99.svg" />
                                <div id="u113_text" class="text ">
                                    <p><span>了解更多</span></p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Unnamed (Group) -->
        <div id="u114" class="ax_default" data-left="1532" data-top="2110" data-width="48" data-height="48"
            layer-opacity="1">

            <!-- Unnamed (Ellipse) -->
            <div id="u115" class="ax_default ellipse">
                <img id="u115_img" class="img " src="../../assets/img/home/u115.svg" />
                <div id="u115_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>

            <!-- Unnamed (Shape) -->
            <div id="u116" class="ax_default box_21">
                <img id="u116_img" class="img " src="../../assets/img/home/u116.svg" />
                <div id="u116_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>
        </div>

        <!-- Unnamed (Group) -->
        <div id="u117" class="ax_default" data-left="100" data-top="2110" data-width="48" data-height="48"
            layer-opacity="1">

            <!-- Unnamed (Ellipse) -->
            <div id="u118" class="ax_default ellipse">
                <img id="u118_img" class="img " src="../../assets/img/home/u115.svg" />
                <div id="u118_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>

            <!-- Unnamed (Shape) -->
            <div id="u119" class="ax_default box_21">
                <img id="u119_img" class="img " src="../../assets/img/home/u119.svg" />
                <div id="u119_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>
        </div>

        <!-- Unnamed (Group) -->
        <div id="u120" class="ax_default" data-left="775" data-top="2450" data-width="130" data-height="28"
            layer-opacity="1">

            <!-- Unnamed (Rectangle) -->
            <div id="u121" class="ax_default label">
                <div id="u121_div" class=""></div>
                <div id="u121_text" class="text ">
                    <p><span>查看所有产品</span></p>
                </div>
            </div>

            <!-- Unnamed (Shape) -->
            <div id="u122" class="ax_default box_21">
                <img id="u122_img" class="img " src="../../assets/img/home/u116.svg" />
                <div id="u122_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>
        </div>

        <!-- Unnamed (Group) -->
        <div id="u123" class="ax_default" data-left="84" data-top="2592" data-width="488" data-height="194"
            layer-opacity="1">

            <!-- Unnamed (Rectangle) -->
            <div id="u124" class="ax_default box_2">
                <div id="u124_div" class=""></div>
                <div id="u124_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>

            <!-- Unnamed (Group) -->
            <div id="u125" class="ax_default" data-left="84" data-top="2625" data-width="488" data-height="128"
                layer-opacity="1">

                <!-- Unnamed (Rectangle) -->
                <div id="u126" class="ax_default label">
                    <div id="u126_div" class=""></div>
                    <div id="u126_text" class="text ">
                        <p><span>专业服务</span></p>
                    </div>
                </div>

                <!-- Unnamed (Rectangle) -->
                <div id="u127" class="ax_default label">
                    <div id="u127_div" class=""></div>
                    <div id="u127_text" class="text ">
                        <p><span>平台使用故障请联系：QQ2823982</span></p>
                    </div>
                </div>

                <!-- Unnamed (Image) -->
                <div id="u128" class="ax_default image">
                    <img id="u128_img" class="img " src="../../assets/img/home/u128.png" />
                    <div id="u128_text" class="text " style="display:none; visibility: hidden">
                        <p></p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Unnamed (Group) -->
        <div id="u129" class="ax_default" data-left="596" data-top="2592" data-width="488" data-height="194"
            layer-opacity="1">

            <!-- Unnamed (Rectangle) -->
            <div id="u130" class="ax_default box_2">
                <div id="u130_div" class=""></div>
                <div id="u130_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>

            <!-- Unnamed (Group) -->
            <div id="u131" class="ax_default" data-left="596" data-top="2625" data-width="488" data-height="128"
                layer-opacity="1">

                <!-- Unnamed (Rectangle) -->
                <div id="u132" class="ax_default label">
                    <div id="u132_div" class=""></div>
                    <div id="u132_text" class="text ">
                        <p><span>售前咨询</span></p>
                    </div>
                </div>

                <!-- Unnamed (Rectangle) -->
                <div id="u133" class="ax_default label">
                    <div id="u133_div" class=""></div>
                    <div id="u133_text" class="text ">
                        <p><span>具体需求可联系设计院，联系号码：13xxxxxxxx</span></p>
                    </div>
                </div>

                <!-- Unnamed (Image) -->
                <div id="u134" class="ax_default image">
                    <img id="u134_img" class="img " src="../../assets/img/home/u134.png" />
                    <div id="u134_text" class="text " style="display:none; visibility: hidden">
                        <p></p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Unnamed (Group) -->
        <div id="u135" class="ax_default" data-left="1108" data-top="2592" data-width="488" data-height="194"
            layer-opacity="1">

            <!-- Unnamed (Rectangle) -->
            <div id="u136" class="ax_default box_2">
                <div id="u136_div" class=""></div>
                <div id="u136_text" class="text " style="display:none; visibility: hidden">
                    <p></p>
                </div>
            </div>

            <!-- Unnamed (Group) -->
            <div id="u137" class="ax_default" data-left="1108" data-top="2625" data-width="488" data-height="128"
                layer-opacity="1">

                <!-- Unnamed (Rectangle) -->
                <div id="u138" class="ax_default label">
                    <div id="u138_div" class=""></div>
                    <div id="u138_text" class="text ">
                        <p><span>需求登记</span></p>
                    </div>
                </div>

                <!-- Unnamed (Rectangle) -->
                <div id="u139" class="ax_default label">
                    <div id="u139_div" class=""></div>
                    <div id="u139_text" class="text ">
                        <p><span>登记您对解决方案支撑的需求</span></p>
                    </div>
                </div>

                <!-- Unnamed (Image) -->
                <div id="u140" class="ax_default image">
                    <img id="u140_img" class="img " src="../../assets/img/home/u140.png" />
                    <div id="u140_text" class="text " style="display:none; visibility: hidden">
                        <p></p>
                    </div>
                </div>
            </div>
        </div>

        <!-- 顶部导航 (Dynamic Panel) -->
        <div id="u143" class="ax_default" data-label="顶部导航">
            <div id="u143_state0" class="panel_state" data-label="State1" style="">
                <div id="u143_state0_content" class="panel_state_content">

                    <!-- 分类导航0 (Dynamic Panel) -->
                    <div id="u144" class="ax_default ax_default_hidden" data-label="分类导航0"
                        style="display:none; visibility: hidden">
                        <div id="u144_state0" class="panel_state" data-label="活动" style="">
                            <div id="u144_state0_content" class="panel_state_content">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u145" class="ax_default _默认样式">
                                    <div id="u145_div" class=""></div>
                                    <div id="u145_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u146" class="ax_default" data-left="40" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u147" class="ax_default box_2">
                                        <div id="u147_div" class=""></div>
                                        <div id="u147_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u148" class="ax_default _默认样式">
                                        <div id="u148_div" class=""></div>
                                        <div id="u148_text" class="text ">
                                            <p><span>免费体验中心</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u149" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u149_div" class=""></div>
                                        <div id="u149_text" class="text ">
                                            <p><span>90+款免费云产品，15+款长期免费云产品</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u150" class="ax_default image">
                                        <img id="u150_img" class="img " src="../../assets/img/home/u150.png" />
                                        <div id="u150_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u151" class="ax_default" data-left="60" data-top="40" data-width="164"
                                    data-height="36" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u152" class="ax_default heading_2">
                                        <div id="u152_div" class=""></div>
                                        <div id="u152_text" class="text ">
                                            <p><span>查看全部活动</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u153" class="ax_default box_21">
                                        <img id="u153_img" class="img " src="../../assets/img/home/u116.svg" />
                                        <div id="u153_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u154" class="ax_default" data-left="40" data-top="186" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u155" class="ax_default box_2">
                                        <div id="u155_div" class=""></div>
                                        <div id="u155_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u156" class="ax_default _默认样式">
                                        <div id="u156_div" class=""></div>
                                        <div id="u156_text" class="text ">
                                            <p><span>绽放计划</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u157" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u157_div" class=""></div>
                                        <div id="u157_text" class="text ">
                                            <p><span>艾斯云与IT服务企业共同成长</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u158" class="ax_default" data-left="398" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u159" class="ax_default box_2">
                                        <div id="u159_div" class=""></div>
                                        <div id="u159_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u160" class="ax_default _默认样式">
                                        <div id="u160_div" class=""></div>
                                        <div id="u160_text" class="text ">
                                            <p><span>艾斯云营销季</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u161" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u161_div" class=""></div>
                                        <div id="u161_text" class="text ">
                                            <p><span>艾斯云耀新品性价比之选</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u162" class="ax_default image">
                                        <img id="u162_img" class="img " src="../../assets/img/home/u150.png" />
                                        <div id="u162_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u163" class="ax_default" data-left="398" data-top="186" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u164" class="ax_default box_2">
                                        <div id="u164_div" class=""></div>
                                        <div id="u164_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u165" class="ax_default _默认样式">
                                        <div id="u165_div" class=""></div>
                                        <div id="u165_text" class="text ">
                                            <p><span>云云协同创新峰会2023</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u166" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u166_div" class=""></div>
                                        <div id="u166_text" class="text ">
                                            <p><span>释放数字生产力</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u167" class="ax_default" data-left="756" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u168" class="ax_default box_2">
                                        <div id="u168_div" class=""></div>
                                        <div id="u168_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u169" class="ax_default _默认样式">
                                        <div id="u169_div" class=""></div>
                                        <div id="u169_text" class="text ">
                                            <p><span>联机游戏</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u170" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u170_div" class=""></div>
                                        <div id="u170_text" class="text ">
                                            <p><span>《幻兽帕鲁》玩家之选</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u171" class="ax_default" data-left="756" data-top="186" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u172" class="ax_default box_2">
                                        <div id="u172_div" class=""></div>
                                        <div id="u172_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u173" class="ax_default _默认样式">
                                        <div id="u173_div" class=""></div>
                                        <div id="u173_text" class="text ">
                                            <p><span>&nbsp;全球创业者峰会</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u174" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u174_div" class=""></div>
                                        <div id="u174_text" class="text ">
                                            <p><span>预见创业者的力量，同行启未来</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u175" class="ax_default" data-left="1114" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u176" class="ax_default box_2">
                                        <div id="u176_div" class=""></div>
                                        <div id="u176_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u177" class="ax_default _默认样式">
                                        <div id="u177_div" class=""></div>
                                        <div id="u177_text" class="text ">
                                            <p><span>商务发展平台BDP</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u178" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u178_div" class=""></div>
                                        <div id="u178_text" class="text ">
                                            <p><span>智能解决方案，助力业务增长</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- 关闭 (Shape) -->
                                <div id="u179" class="ax_default icon" data-label="关闭">
                                    <img id="u179_img" class="img " src="../../assets/img/home/关闭_u179.svg" />
                                    <div id="u179_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u144_state1" class="panel_state" data-label="产品" style="visibility: hidden;">
                            <div id="u144_state1_content" class="panel_state_content">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u180" class="ax_default _默认样式">
                                    <div id="u180_div" class=""></div>
                                    <div id="u180_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- 关闭 (Shape) -->
                                <div id="u181" class="ax_default icon" data-label="关闭">
                                    <img id="u181_img" class="img " src="../../assets/img/home/关闭_u179.svg" />
                                    <div id="u181_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u182" class="ax_default _默认样式 selected" selectiongroup="u142b11">
                                    <div id="u182_div" class="selected"></div>
                                    <div id="u182_text" class="text ">
                                        <p><span>精选推荐</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u183" class="ax_default" data-left="418" data-top="40" data-width="164"
                                    data-height="36" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u184" class="ax_default heading_2">
                                        <div id="u184_div" class=""></div>
                                        <div id="u184_text" class="text ">
                                            <p><span>查看所有产品</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u185" class="ax_default box_21">
                                        <img id="u185_img" class="img " src="../../assets/img/home/u116.svg" />
                                        <div id="u185_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u186" class="ax_default" data-left="398" data-top="108" data-width="338"
                                    data-height="120" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u187" class="ax_default box_2">
                                        <div id="u187_div" class=""></div>
                                        <div id="u187_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u188" class="ax_default image">
                                        <img id="u188_img" class="img " src="../../assets/img/home/u188.png" />
                                        <div id="u188_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u189" class="ax_default _默认样式">
                                        <div id="u189_div" class=""></div>
                                        <div id="u189_text" class="text ">
                                            <p><span>云耀云服务器 HECS</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u190" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u190_div" class=""></div>
                                        <div id="u190_text" class="text ">
                                            <p><span>面向中低载应用场景的轻量级云服务器</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u191" class="ax_default" data-left="60" data-top="40" data-width="240"
                                    data-height="32" layer-opacity="1">

                                    <!-- 背景框 (Rectangle) -->
                                    <div id="u192" class="ax_default box_1" data-label="背景框">
                                        <div id="u192_div" class=""></div>
                                        <div id="u192_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- 文本 (Text Field) -->
                                    <div id="u193" class="ax_default text_field" data-label="文本">
                                        <div id="u193_div" class=""></div>
                                        <input id="u193_input" type="text" value="" class="u193_input" />
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u194" class="ax_default _形状">
                                        <img id="u194_img" class="img " src="../../assets/img/home/u194.svg" />
                                        <div id="u194_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u195" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u195_div" class=""></div>
                                    <div id="u195_text" class="text ">
                                        <p><span>计算</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u196" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u196_div" class=""></div>
                                    <div id="u196_text" class="text ">
                                        <p><span>存储</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u197" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u197_div" class=""></div>
                                    <div id="u197_text" class="text ">
                                        <p><span>网络</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u198" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u198_div" class=""></div>
                                    <div id="u198_text" class="text ">
                                        <p><span>CDN与智能边缘</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u199" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u199_div" class=""></div>
                                    <div id="u199_text" class="text ">
                                        <p><span>数据库</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u200" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u200_div" class=""></div>
                                    <div id="u200_text" class="text ">
                                        <p><span>人工智能</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u201" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u201_div" class=""></div>
                                    <div id="u201_text" class="text ">
                                        <p><span>大数据</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u202" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u202_div" class=""></div>
                                    <div id="u202_text" class="text ">
                                        <p><span>loT物联网</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u203" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u203_div" class=""></div>
                                    <div id="u203_text" class="text ">
                                        <p><span>应用中间件</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u204" class="ax_default _默认样式" selectiongroup="u142b11">
                                    <div id="u204_div" class=""></div>
                                    <div id="u204_text" class="text ">
                                        <p><span>开发与运维</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u205" class="ax_default" data-left="756" data-top="108" data-width="338"
                                    data-height="120" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u206" class="ax_default box_2">
                                        <div id="u206_div" class=""></div>
                                        <div id="u206_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u207" class="ax_default image">
                                        <img id="u207_img" class="img " src="../../assets/img/home/u207.png" />
                                        <div id="u207_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u208" class="ax_default _默认样式">
                                        <div id="u208_div" class=""></div>
                                        <div id="u208_text" class="text ">
                                            <p><span>弹性公网IP EIP</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u209" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u209_div" class=""></div>
                                        <div id="u209_text" class="text ">
                                            <p><span>提供独立的公网IP资源</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u210" class="ax_default" data-left="1114" data-top="108" data-width="338"
                                    data-height="120" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u211" class="ax_default box_2">
                                        <div id="u211_div" class=""></div>
                                        <div id="u211_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u212" class="ax_default image">
                                        <img id="u212_img" class="img " src="../../assets/img/home/u212.png" />
                                        <div id="u212_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u213" class="ax_default _默认样式">
                                        <div id="u213_div" class=""></div>
                                        <div id="u213_text" class="text ">
                                            <p><span>弹性负载均衡 ELB</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u214" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u214_div" class=""></div>
                                        <div id="u214_text" class="text ">
                                            <p><span>将流量自动分发到多台云服务器</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u215" class="ax_default" data-left="398" data-top="248" data-width="338"
                                    data-height="120" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u216" class="ax_default box_2">
                                        <div id="u216_div" class=""></div>
                                        <div id="u216_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u217" class="ax_default _默认样式">
                                        <div id="u217_div" class=""></div>
                                        <div id="u217_text" class="text ">
                                            <p><span>虚拟私有云 VPC</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u218" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u218_div" class=""></div>
                                        <div id="u218_text" class="text ">
                                            <p><span>隔离的、私密的虚拟网络环境</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u219" class="ax_default image">
                                        <img id="u219_img" class="img " src="../../assets/img/home/u219.png" />
                                        <div id="u219_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u220" class="ax_default" data-left="756" data-top="248" data-width="338"
                                    data-height="120" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u221" class="ax_default box_2">
                                        <div id="u221_div" class=""></div>
                                        <div id="u221_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u222" class="ax_default image">
                                        <img id="u222_img" class="img " src="../../assets/img/home/u207.png" />
                                        <div id="u222_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u223" class="ax_default _默认样式">
                                        <div id="u223_div" class=""></div>
                                        <div id="u223_text" class="text ">
                                            <p><span>弹性公网IP EIP</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u224" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u224_div" class=""></div>
                                        <div id="u224_text" class="text ">
                                            <p><span>提供独立的公网IP资源</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u225" class="ax_default" data-left="1114" data-top="248" data-width="338"
                                    data-height="120" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u226" class="ax_default box_2">
                                        <div id="u226_div" class=""></div>
                                        <div id="u226_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u227" class="ax_default image">
                                        <img id="u227_img" class="img " src="../../assets/img/home/u212.png" />
                                        <div id="u227_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u228" class="ax_default _默认样式">
                                        <div id="u228_div" class=""></div>
                                        <div id="u228_text" class="text ">
                                            <p><span>弹性负载均衡 ELB</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u229" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u229_div" class=""></div>
                                        <div id="u229_text" class="text ">
                                            <p><span>将流量自动分发到多台云服务器</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u230" class="ax_default" data-left="398" data-top="388" data-width="338"
                                    data-height="120" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u231" class="ax_default box_2">
                                        <div id="u231_div" class=""></div>
                                        <div id="u231_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u232" class="ax_default _默认样式">
                                        <div id="u232_div" class=""></div>
                                        <div id="u232_text" class="text ">
                                            <p><span>虚拟私有云 VPC</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u233" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u233_div" class=""></div>
                                        <div id="u233_text" class="text ">
                                            <p><span>隔离的、私密的虚拟网络环境</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u234" class="ax_default image">
                                        <img id="u234_img" class="img " src="../../assets/img/home/u219.png" />
                                        <div id="u234_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u235" class="ax_default" data-left="756" data-top="388" data-width="338"
                                    data-height="120" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u236" class="ax_default box_2">
                                        <div id="u236_div" class=""></div>
                                        <div id="u236_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u237" class="ax_default image">
                                        <img id="u237_img" class="img " src="../../assets/img/home/u207.png" />
                                        <div id="u237_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u238" class="ax_default _默认样式">
                                        <div id="u238_div" class=""></div>
                                        <div id="u238_text" class="text ">
                                            <p><span>弹性公网IP EIP</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u239" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u239_div" class=""></div>
                                        <div id="u239_text" class="text ">
                                            <p><span>提供独立的公网IP资源</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u240" class="ax_default" data-left="1114" data-top="388" data-width="338"
                                    data-height="120" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u241" class="ax_default box_2">
                                        <div id="u241_div" class=""></div>
                                        <div id="u241_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Image) -->
                                    <div id="u242" class="ax_default image">
                                        <img id="u242_img" class="img " src="../../assets/img/home/u212.png" />
                                        <div id="u242_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u243" class="ax_default _默认样式">
                                        <div id="u243_div" class=""></div>
                                        <div id="u243_text" class="text ">
                                            <p><span>弹性负载均衡 ELB</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u244" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u244_div" class=""></div>
                                        <div id="u244_text" class="text ">
                                            <p><span>将流量自动分发到多台云服务器</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u144_state2" class="panel_state" data-label="解决方案" style="visibility: hidden;">
                            <div id="u144_state2_content" class="panel_state_content">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u245" class="ax_default _默认样式">
                                    <div id="u245_div" class=""></div>
                                    <div id="u245_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u246" class="ax_default" data-left="60" data-top="40" data-width="214"
                                    data-height="36" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u247" class="ax_default heading_2">
                                        <div id="u247_div" class=""></div>
                                        <div id="u247_text" class="text ">
                                            <p><span>查看所有解决方案</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u248" class="ax_default box_21">
                                        <img id="u248_img" class="img " src="../../assets/img/home/u116.svg" />
                                        <div id="u248_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u249" class="ax_default" data-left="398" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u250" class="ax_default box_2">
                                        <div id="u250_div" class=""></div>
                                        <div id="u250_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u251" class="ax_default _默认样式">
                                        <div id="u251_div" class=""></div>
                                        <div id="u251_text" class="text ">
                                            <p><span>电信</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u252" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u252_div" class=""></div>
                                        <div id="u252_text" class="text ">
                                            <p><span>使能运营商网络变现、业务创新、运营提效</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u253" class="ax_default" data-left="398" data-top="186" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u254" class="ax_default box_2">
                                        <div id="u254_div" class=""></div>
                                        <div id="u254_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u255" class="ax_default _默认样式">
                                        <div id="u255_div" class=""></div>
                                        <div id="u255_text" class="text ">
                                            <p><span>电商</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u256" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u256_div" class=""></div>
                                        <div id="u256_text" class="text ">
                                            <p><span>释放数字生产力</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u257" class="ax_default" data-left="756" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u258" class="ax_default box_2">
                                        <div id="u258_div" class=""></div>
                                        <div id="u258_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u259" class="ax_default _默认样式">
                                        <div id="u259_div" class=""></div>
                                        <div id="u259_text" class="text ">
                                            <p><span>汽车</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u260" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u260_div" class=""></div>
                                        <div id="u260_text" class="text ">
                                            <p><span>助力汽车行业数字化转型</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u261" class="ax_default" data-left="756" data-top="186" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u262" class="ax_default box_2">
                                        <div id="u262_div" class=""></div>
                                        <div id="u262_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u263" class="ax_default _默认样式">
                                        <div id="u263_div" class=""></div>
                                        <div id="u263_text" class="text ">
                                            <p><span>教育</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u264" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u264_div" class=""></div>
                                        <div id="u264_text" class="text ">
                                            <p><span>预见创业者的力量，同行启未来</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u265" class="ax_default" data-left="1114" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u266" class="ax_default box_2">
                                        <div id="u266_div" class=""></div>
                                        <div id="u266_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u267" class="ax_default _默认样式">
                                        <div id="u267_div" class=""></div>
                                        <div id="u267_text" class="text ">
                                            <p><span>城市智能体</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u268" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u268_div" class=""></div>
                                        <div id="u268_text" class="text ">
                                            <p><span>聚焦城市服务对象，提升用户体验</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- 关闭 (Shape) -->
                                <div id="u269" class="ax_default icon" data-label="关闭">
                                    <img id="u269_img" class="img " src="../../assets/img/home/关闭_u179.svg" />
                                    <div id="u269_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u270" class="ax_default" data-left="1114" data-top="186" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u271" class="ax_default box_2">
                                        <div id="u271_div" class=""></div>
                                        <div id="u271_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u272" class="ax_default _默认样式">
                                        <div id="u272_div" class=""></div>
                                        <div id="u272_text" class="text ">
                                            <p><span>金融</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u273" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u273_div" class=""></div>
                                        <div id="u273_text" class="text ">
                                            <p><span>预见创业者的力量，同行启未来</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u274" class="ax_default" data-left="398" data-top="284" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u275" class="ax_default box_2">
                                        <div id="u275_div" class=""></div>
                                        <div id="u275_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u276" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u276_div" class=""></div>
                                        <div id="u276_text" class="text ">
                                            <p><span>艾斯云耀新品性价比之选</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u277" class="ax_default _默认样式">
                                        <div id="u277_div" class=""></div>
                                        <div id="u277_text" class="text ">
                                            <p><span>游戏</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u278" class="ax_default" data-left="756" data-top="284" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u279" class="ax_default box_2">
                                        <div id="u279_div" class=""></div>
                                        <div id="u279_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u280" class="ax_default _默认样式">
                                        <div id="u280_div" class=""></div>
                                        <div id="u280_text" class="text ">
                                            <p><span>医疗健康</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u281" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u281_div" class=""></div>
                                        <div id="u281_text" class="text ">
                                            <p><span>《幻兽帕鲁》玩家之选</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u282" class="ax_default _默认样式 selected" selectiongroup="u142b13">
                                    <div id="u282_div" class="selected"></div>
                                    <div id="u282_text" class="text ">
                                        <p><span>行业解决方案</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u283" class="ax_default" data-left="398" data-top="382" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u284" class="ax_default box_2">
                                        <div id="u284_div" class=""></div>
                                        <div id="u284_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u285" class="ax_default _默认样式">
                                        <div id="u285_div" class=""></div>
                                        <div id="u285_text" class="text ">
                                            <p><span>媒体文娱</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u286" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u286_div" class=""></div>
                                        <div id="u286_text" class="text ">
                                            <p><span>释放数字生产力</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u287" class="ax_default" data-left="1114" data-top="284" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u288" class="ax_default box_2">
                                        <div id="u288_div" class=""></div>
                                        <div id="u288_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u289" class="ax_default _默认样式">
                                        <div id="u289_div" class=""></div>
                                        <div id="u289_text" class="text ">
                                            <p><span>制造</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u290" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u290_div" class=""></div>
                                        <div id="u290_text" class="text ">
                                            <p><span>智能解决方案，助力业务增长</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u291" class="ax_default _默认样式" selectiongroup="u142b13">
                                    <div id="u291_div" class=""></div>
                                    <div id="u291_text" class="text ">
                                        <p><span>通用解决方案 </span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u292" class="ax_default" data-left="756" data-top="382" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u293" class="ax_default box_2">
                                        <div id="u293_div" class=""></div>
                                        <div id="u293_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u294" class="ax_default _默认样式">
                                        <div id="u294_div" class=""></div>
                                        <div id="u294_text" class="text ">
                                            <p><span>零售</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u295" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u295_div" class=""></div>
                                        <div id="u295_text" class="text ">
                                            <p><span>预见创业者的力量，同行启未来</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u296" class="ax_default _默认样式" selectiongroup="u142b13">
                                    <div id="u296_div" class=""></div>
                                    <div id="u296_text" class="text ">
                                        <p><span>企业上云中心</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u297" class="ax_default _默认样式" selectiongroup="u142b13">
                                    <div id="u297_div" class=""></div>
                                    <div id="u297_text" class="text ">
                                        <p><span>解决方案实践</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u298" class="ax_default" data-left="1114" data-top="382" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u299" class="ax_default box_2">
                                        <div id="u299_div" class=""></div>
                                        <div id="u299_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u300" class="ax_default _默认样式">
                                        <div id="u300_div" class=""></div>
                                        <div id="u300_text" class="text ">
                                            <p><span>智慧物流</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u301" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u301_div" class=""></div>
                                        <div id="u301_text" class="text ">
                                            <p><span>预见创业者的力量，同行启未来</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u144_state3" class="panel_state" data-label="定价" style="visibility: hidden;">
                            <div id="u144_state3_content" class="panel_state_content">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u302" class="ax_default _默认样式">
                                    <div id="u302_div" class=""></div>
                                    <div id="u302_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u303" class="ax_default" data-left="40" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u304" class="ax_default box_2">
                                        <div id="u304_div" class=""></div>
                                        <div id="u304_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u305" class="ax_default _默认样式">
                                        <div id="u305_div" class=""></div>
                                        <div id="u305_text" class="text ">
                                            <p><span>价格计算器</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u306" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u306_div" class=""></div>
                                        <div id="u306_text" class="text ">
                                            <p><span>准确预估成本，灵活购买服务</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u307" class="ax_default" data-left="60" data-top="40" data-width="164"
                                    data-height="36" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u308" class="ax_default heading_2">
                                        <div id="u308_div" class=""></div>
                                        <div id="u308_text" class="text ">
                                            <p><span>了解产品定价</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u309" class="ax_default box_21">
                                        <img id="u309_img" class="img " src="../../assets/img/home/u116.svg" />
                                        <div id="u309_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u310" class="ax_default" data-left="398" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u311" class="ax_default box_2">
                                        <div id="u311_div" class=""></div>
                                        <div id="u311_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u312" class="ax_default _默认样式">
                                        <div id="u312_div" class=""></div>
                                        <div id="u312_text" class="text ">
                                            <p><span>定价策略</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u313" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u313_div" class=""></div>
                                        <div id="u313_text" class="text ">
                                            <p><span>多种付费模式，根据业务需求灵活调整</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- 关闭 (Shape) -->
                                <div id="u314" class="ax_default icon" data-label="关闭">
                                    <img id="u314_img" class="img " src="../../assets/img/home/关闭_u179.svg" />
                                    <div id="u314_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u144_state4" class="panel_state" data-label="云商店" style="visibility: hidden;">
                            <div id="u144_state4_content" class="panel_state_content">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u315" class="ax_default _默认样式">
                                    <div id="u315_div" class=""></div>
                                    <div id="u315_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u316" class="ax_default" data-left="40" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u317" class="ax_default box_2">
                                        <div id="u317_div" class=""></div>
                                        <div id="u317_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u318" class="ax_default _默认样式">
                                        <div id="u318_div" class=""></div>
                                        <div id="u318_text" class="text ">
                                            <p><span>基础设施软件</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u319" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u319_div" class=""></div>
                                        <div id="u319_text" class="text ">
                                            <p><span>数据库与缓存、内容管理等软件与服务</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u320" class="ax_default" data-left="60" data-top="40" data-width="143"
                                    data-height="36" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u321" class="ax_default heading_2">
                                        <div id="u321_div" class=""></div>
                                        <div id="u321_text" class="text ">
                                            <p><span>进入云商店</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u322" class="ax_default box_21">
                                        <img id="u322_img" class="img " src="../../assets/img/home/u116.svg" />
                                        <div id="u322_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u323" class="ax_default" data-left="398" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u324" class="ax_default box_2">
                                        <div id="u324_div" class=""></div>
                                        <div id="u324_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u325" class="ax_default _默认样式">
                                        <div id="u325_div" class=""></div>
                                        <div id="u325_text" class="text ">
                                            <p><span>业务软件</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u326" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u326_div" class=""></div>
                                        <div id="u326_text" class="text ">
                                            <p><span>企业智能、企业应用等软件与服务</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- 关闭 (Shape) -->
                                <div id="u327" class="ax_default icon" data-label="关闭">
                                    <img id="u327_img" class="img " src="../../assets/img/home/关闭_u179.svg" />
                                    <div id="u327_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u328" class="ax_default" data-left="756" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u329" class="ax_default box_2">
                                        <div id="u329_div" class=""></div>
                                        <div id="u329_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u330" class="ax_default _默认样式">
                                        <div id="u330_div" class=""></div>
                                        <div id="u330_text" class="text ">
                                            <p><span>开发者工具</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u331" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u331_div" class=""></div>
                                        <div id="u331_text" class="text ">
                                            <p><span>中间件、日志分析等软件与服务</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u332" class="ax_default" data-left="1114" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u333" class="ax_default box_2">
                                        <div id="u333_div" class=""></div>
                                        <div id="u333_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u334" class="ax_default _默认样式">
                                        <div id="u334_div" class=""></div>
                                        <div id="u334_text" class="text ">
                                            <p><span>专业服务</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u335" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u335_div" class=""></div>
                                        <div id="u335_text" class="text ">
                                            <p><span>环境配置及维护服务</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u144_state5" class="panel_state" data-label="合作伙伴" style="visibility: hidden;">
                            <div id="u144_state5_content" class="panel_state_content">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u336" class="ax_default _默认样式">
                                    <div id="u336_div" class=""></div>
                                    <div id="u336_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u337" class="ax_default" data-left="40" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u338" class="ax_default box_2">
                                        <div id="u338_div" class=""></div>
                                        <div id="u338_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u339" class="ax_default _默认样式">
                                        <div id="u339_div" class=""></div>
                                        <div id="u339_text" class="text ">
                                            <p><span>软件伙伴发展路径</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u340" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u340_div" class=""></div>
                                        <div id="u340_text" class="text ">
                                            <p><span>支撑伙伴在艾斯云上构建软件方案</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u341" class="ax_default" data-left="60" data-top="40" data-width="213"
                                    data-height="36" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u342" class="ax_default heading_2">
                                        <div id="u342_div" class=""></div>
                                        <div id="u342_text" class="text ">
                                            <p><span>了解合作伙伴体系</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u343" class="ax_default box_21">
                                        <img id="u343_img" class="img " src="../../assets/img/home/u116.svg" />
                                        <div id="u343_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u344" class="ax_default" data-left="398" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u345" class="ax_default box_2">
                                        <div id="u345_div" class=""></div>
                                        <div id="u345_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u346" class="ax_default _默认样式">
                                        <div id="u346_div" class=""></div>
                                        <div id="u346_text" class="text ">
                                            <p><span>合作伙伴能力计划</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u347" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u347_div" class=""></div>
                                        <div id="u347_text" class="text ">
                                            <p><span>为合作伙伴提供能力标签认证标准及流程</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- 关闭 (Shape) -->
                                <div id="u348" class="ax_default icon" data-label="关闭">
                                    <img id="u348_img" class="img " src="../../assets/img/home/关闭_u179.svg" />
                                    <div id="u348_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u349" class="ax_default" data-left="756" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u350" class="ax_default box_2">
                                        <div id="u350_div" class=""></div>
                                        <div id="u350_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u351" class="ax_default _默认样式">
                                        <div id="u351_div" class=""></div>
                                        <div id="u351_text" class="text ">
                                            <p><span>报名参加培训</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u352" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u352_div" class=""></div>
                                        <div id="u352_text" class="text ">
                                            <p><span>选择对应的培训路径，取得相应专业鉴定</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u353" class="ax_default" data-left="1114" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u354" class="ax_default box_2">
                                        <div id="u354_div" class=""></div>
                                        <div id="u354_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u355" class="ax_default _默认样式">
                                        <div id="u355_div" class=""></div>
                                        <div id="u355_text" class="text ">
                                            <p><span>登录伙伴中心</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u356" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u356_div" class=""></div>
                                        <div id="u356_text" class="text ">
                                            <p><span>进入合作伙伴作业平台高效开展业务</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u357" class="ax_default" data-left="40" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u358" class="ax_default box_2">
                                        <div id="u358_div" class=""></div>
                                        <div id="u358_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u359" class="ax_default _默认样式">
                                        <div id="u359_div" class=""></div>
                                        <div id="u359_text" class="text ">
                                            <p><span>服务伙伴发展路径</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u360" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u360_div" class=""></div>
                                        <div id="u360_text" class="text ">
                                            <p><span>助力伙伴构建云上核心服务能力</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u361" class="ax_default" data-left="756" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u362" class="ax_default box_2">
                                        <div id="u362_div" class=""></div>
                                        <div id="u362_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u363" class="ax_default _默认样式">
                                        <div id="u363_div" class=""></div>
                                        <div id="u363_text" class="text ">
                                            <p><span>获得艾斯云认证</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u364" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u364_div" class=""></div>
                                        <div id="u364_text" class="text ">
                                            <p><span>提供个性化课程，帮助您培养专业技能</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u365" class="ax_default" data-left="398" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u366" class="ax_default box_2">
                                        <div id="u366_div" class=""></div>
                                        <div id="u366_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u367" class="ax_default _默认样式">
                                        <div id="u367_div" class=""></div>
                                        <div id="u367_text" class="text ">
                                            <p><span>解决方案提供商计划</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u368" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u368_div" class=""></div>
                                        <div id="u368_text" class="text ">
                                            <p><span>销售和交付艾斯云服务及解决方案</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u369" class="ax_default" data-left="40" data-top="108" data-width="153"
                                    data-height="20" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u370" class="ax_default _默认样式">
                                        <div id="u370_div" class=""></div>
                                        <div id="u370_text" class="text ">
                                            <p><span>软件伙伴发展路径</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u371" class="ax_default box_21">
                                        <img id="u371_img" class="img " src="../../assets/img/home/u371.svg" />
                                        <div id="u371_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u372" class="ax_default" data-left="398" data-top="108" data-width="97"
                                    data-height="20" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u373" class="ax_default _默认样式">
                                        <div id="u373_div" class=""></div>
                                        <div id="u373_text" class="text ">
                                            <p><span>伙伴计划</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u374" class="ax_default box_21">
                                        <img id="u374_img" class="img " src="../../assets/img/home/u371.svg" />
                                        <div id="u374_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u375" class="ax_default _默认样式">
                                    <div id="u375_div" class=""></div>
                                    <div id="u375_text" class="text ">
                                        <p><span>培训与支持</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u376" class="ax_default _默认样式">
                                    <div id="u376_div" class=""></div>
                                    <div id="u376_text" class="text ">
                                        <p><span>更多支持</span></p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u144_state6" class="panel_state" data-label="开发者" style="visibility: hidden;">
                            <div id="u144_state6_content" class="panel_state_content">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u377" class="ax_default _默认样式">
                                    <div id="u377_div" class=""></div>
                                    <div id="u377_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u378" class="ax_default" data-left="40" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u379" class="ax_default box_2">
                                        <div id="u379_div" class=""></div>
                                        <div id="u379_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u380" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u380_div" class=""></div>
                                        <div id="u380_text" class="text ">
                                            <p><span>获取海量开发者技术资源、工具</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u381" class="ax_default _默认样式">
                                    <div id="u381_div" class=""></div>
                                    <div id="u381_text" class="text ">
                                        <p><span>开发工具</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u382" class="ax_default" data-left="60" data-top="40" data-width="143"
                                    data-height="36" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u383" class="ax_default heading_2">
                                        <div id="u383_div" class=""></div>
                                        <div id="u383_text" class="text ">
                                            <p><span>进入开发者</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u384" class="ax_default box_21">
                                        <img id="u384_img" class="img " src="../../assets/img/home/u116.svg" />
                                        <div id="u384_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u385" class="ax_default" data-left="398" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u386" class="ax_default box_2">
                                        <div id="u386_div" class=""></div>
                                        <div id="u386_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u387" class="ax_default _默认样式">
                                        <div id="u387_div" class=""></div>
                                        <div id="u387_text" class="text ">
                                            <p><span>开发者计划</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u388" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u388_div" class=""></div>
                                        <div id="u388_text" class="text ">
                                            <p><span>使能开发者基于开放能力进行技术创新</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- 关闭 (Shape) -->
                                <div id="u389" class="ax_default icon" data-label="关闭">
                                    <img id="u389_img" class="img " src="../../assets/img/home/关闭_u179.svg" />
                                    <div id="u389_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u390" class="ax_default" data-left="756" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u391" class="ax_default box_2">
                                        <div id="u391_div" class=""></div>
                                        <div id="u391_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u392" class="ax_default _默认样式">
                                        <div id="u392_div" class=""></div>
                                        <div id="u392_text" class="text ">
                                            <p><span>开发支持</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u393" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u393_div" class=""></div>
                                        <div id="u393_text" class="text ">
                                            <p><span>专业高效的开发者在线技术支持服务</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u394" class="ax_default" data-left="1114" data-top="88" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u395" class="ax_default box_2">
                                        <div id="u395_div" class=""></div>
                                        <div id="u395_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u396" class="ax_default _默认样式">
                                        <div id="u396_div" class=""></div>
                                        <div id="u396_text" class="text ">
                                            <p><span>论坛</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u397" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u397_div" class=""></div>
                                        <div id="u397_text" class="text ">
                                            <p><span>专家技术布道、开发者交流分享的平台</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u398" class="ax_default" data-left="40" data-top="186" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u399" class="ax_default box_2">
                                        <div id="u399_div" class=""></div>
                                        <div id="u399_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u400" class="ax_default _默认样式">
                                        <div id="u400_div" class=""></div>
                                        <div id="u400_text" class="text ">
                                            <p><span>学堂</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u401" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u401_div" class=""></div>
                                        <div id="u401_text" class="text ">
                                            <p><span>云上学习、实验、认证与培训服务</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u402" class="ax_default" data-left="398" data-top="186" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u403" class="ax_default box_2">
                                        <div id="u403_div" class=""></div>
                                        <div id="u403_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u404" class="ax_default _默认样式">
                                        <div id="u404_div" class=""></div>
                                        <div id="u404_text" class="text ">
                                            <p><span>活动</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u405" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u405_div" class=""></div>
                                        <div id="u405_text" class="text ">
                                            <p><span>开发者实训、热门活动专区</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u406" class="ax_default" data-left="756" data-top="186" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u407" class="ax_default box_2">
                                        <div id="u407_div" class=""></div>
                                        <div id="u407_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u408" class="ax_default _默认样式">
                                        <div id="u408_div" class=""></div>
                                        <div id="u408_text" class="text ">
                                            <p><span>大赛</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u409" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u409_div" class=""></div>
                                        <div id="u409_text" class="text ">
                                            <p><span>解决实际问题的竞技舞台，助力技术创新实践</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u144_state7" class="panel_state" data-label="支持与服务" style="visibility: hidden;">
                            <div id="u144_state7_content" class="panel_state_content">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u410" class="ax_default _默认样式">
                                    <div id="u410_div" class=""></div>
                                    <div id="u410_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u411" class="ax_default" data-left="40" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u412" class="ax_default box_2">
                                        <div id="u412_div" class=""></div>
                                        <div id="u412_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u413" class="ax_default _默认样式">
                                        <div id="u413_div" class=""></div>
                                        <div id="u413_text" class="text ">
                                            <p><span>自助服务</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u414" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u414_div" class=""></div>
                                        <div id="u414_text" class="text ">
                                            <p><span>提供常见问题答案和便捷运维工具</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u415" class="ax_default" data-left="60" data-top="40" data-width="203"
                                    data-height="36" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u416" class="ax_default heading_2">
                                        <div id="u416_div" class=""></div>
                                        <div id="u416_text" class="text ">
                                            <p><span>了解支持与服务</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u417" class="ax_default box_21">
                                        <img id="u417_img" class="img " src="../../assets/img/home/u116.svg" />
                                        <div id="u417_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u418" class="ax_default" data-left="398" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u419" class="ax_default box_2">
                                        <div id="u419_div" class=""></div>
                                        <div id="u419_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u420" class="ax_default _默认样式">
                                        <div id="u420_div" class=""></div>
                                        <div id="u420_text" class="text ">
                                            <p><span>支持计划</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u421" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u421_div" class=""></div>
                                        <div id="u421_text" class="text ">
                                            <p><span>获取独特的工具和专业知识</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- 关闭 (Shape) -->
                                <div id="u422" class="ax_default icon" data-label="关闭">
                                    <img id="u422_img" class="img " src="../../assets/img/home/关闭_u179.svg" />
                                    <div id="u422_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u423" class="ax_default" data-left="756" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u424" class="ax_default box_2">
                                        <div id="u424_div" class=""></div>
                                        <div id="u424_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u425" class="ax_default _默认样式">
                                        <div id="u425_div" class=""></div>
                                        <div id="u425_text" class="text ">
                                            <p><span>云产品入门</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u426" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u426_div" class=""></div>
                                        <div id="u426_text" class="text ">
                                            <p><span>5分钟快速掌握云服务常用操作</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u427" class="ax_default" data-left="1114" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u428" class="ax_default box_2">
                                        <div id="u428_div" class=""></div>
                                        <div id="u428_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u429" class="ax_default _默认样式">
                                        <div id="u429_div" class=""></div>
                                        <div id="u429_text" class="text ">
                                            <p><span>售前咨询</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u430" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u430_div" class=""></div>
                                        <div id="u430_text" class="text ">
                                            <p><span>为您提供专业的售前购买咨询</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u431" class="ax_default" data-left="40" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u432" class="ax_default box_2">
                                        <div id="u432_div" class=""></div>
                                        <div id="u432_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u433" class="ax_default _默认样式">
                                        <div id="u433_div" class=""></div>
                                        <div id="u433_text" class="text ">
                                            <p><span>服务保障</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u434" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u434_div" class=""></div>
                                        <div id="u434_text" class="text ">
                                            <p><span>助力伙伴构建云上核心服务能力</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u435" class="ax_default" data-left="756" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u436" class="ax_default box_2">
                                        <div id="u436_div" class=""></div>
                                        <div id="u436_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u437" class="ax_default _默认样式">
                                        <div id="u437_div" class=""></div>
                                        <div id="u437_text" class="text ">
                                            <p><span>视频教程</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u438" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u438_div" class=""></div>
                                        <div id="u438_text" class="text ">
                                            <p><span>提供个性化课程，帮助您培养专业技能</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u439" class="ax_default" data-left="398" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u440" class="ax_default box_2">
                                        <div id="u440_div" class=""></div>
                                        <div id="u440_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u441" class="ax_default _默认样式">
                                        <div id="u441_div" class=""></div>
                                        <div id="u441_text" class="text ">
                                            <p><span>专业服务</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u442" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u442_div" class=""></div>
                                        <div id="u442_text" class="text ">
                                            <p><span>销售和交付艾斯云服务及解决方案</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u443" class="ax_default _默认样式">
                                    <div id="u443_div" class=""></div>
                                    <div id="u443_text" class="text ">
                                        <p><span>培训与支持</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u444" class="ax_default _默认样式">
                                    <div id="u444_div" class=""></div>
                                    <div id="u444_text" class="text ">
                                        <p><span>更多支持</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u445" class="ax_default _默认样式">
                                    <div id="u445_div" class=""></div>
                                    <div id="u445_text" class="text ">
                                        <p><span>客户支持</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u446" class="ax_default _默认样式">
                                    <div id="u446_div" class=""></div>
                                    <div id="u446_text" class="text ">
                                        <p><span>增持服务</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u447" class="ax_default" data-left="1114" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u448" class="ax_default box_2">
                                        <div id="u448_div" class=""></div>
                                        <div id="u448_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u449" class="ax_default _默认样式">
                                        <div id="u449_div" class=""></div>
                                        <div id="u449_text" class="text ">
                                            <p><span>售后支持</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u450" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u450_div" class=""></div>
                                        <div id="u450_text" class="text ">
                                            <p><span>云产品使用问题，坐席工程师为您解答</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u451" class="ax_default" data-left="40" data-top="344" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u452" class="ax_default box_2">
                                        <div id="u452_div" class=""></div>
                                        <div id="u452_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u453" class="ax_default _默认样式">
                                        <div id="u453_div" class=""></div>
                                        <div id="u453_text" class="text ">
                                            <p><span>服务公告</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u454" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u454_div" class=""></div>
                                        <div id="u454_text" class="text ">
                                            <p><span>获悉艾斯云服务相关公告</span></p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="u144_state8" class="panel_state" data-label="了解云" style="visibility: hidden;">
                            <div id="u144_state8_content" class="panel_state_content">

                                <!-- Unnamed (Rectangle) -->
                                <div id="u455" class="ax_default _默认样式">
                                    <div id="u455_div" class=""></div>
                                    <div id="u455_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u456" class="ax_default" data-left="40" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u457" class="ax_default box_2">
                                        <div id="u457_div" class=""></div>
                                        <div id="u457_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u458" class="ax_default _默认样式">
                                        <div id="u458_div" class=""></div>
                                        <div id="u458_text" class="text ">
                                            <p><span>全球产品与服务</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u459" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u459_div" class=""></div>
                                        <div id="u459_text" class="text ">
                                            <p><span>了解全球布局</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u460" class="ax_default" data-left="60" data-top="40" data-width="143"
                                    data-height="36" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u461" class="ax_default heading_2">
                                        <div id="u461_div" class=""></div>
                                        <div id="u461_text" class="text ">
                                            <p><span>了解艾斯云</span></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Shape) -->
                                    <div id="u462" class="ax_default box_21">
                                        <img id="u462_img" class="img " src="../../assets/img/home/u116.svg" />
                                        <div id="u462_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u463" class="ax_default" data-left="398" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u464" class="ax_default box_2">
                                        <div id="u464_div" class=""></div>
                                        <div id="u464_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u465" class="ax_default _默认样式">
                                        <div id="u465_div" class=""></div>
                                        <div id="u465_text" class="text ">
                                            <p><span>新闻资讯</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u466" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u466_div" class=""></div>
                                        <div id="u466_text" class="text ">
                                            <p><span>了解艾斯云最新资讯</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- 关闭 (Shape) -->
                                <div id="u467" class="ax_default icon" data-label="关闭">
                                    <img id="u467_img" class="img " src="../../assets/img/home/关闭_u179.svg" />
                                    <div id="u467_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u468" class="ax_default" data-left="756" data-top="148" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u469" class="ax_default box_2">
                                        <div id="u469_div" class=""></div>
                                        <div id="u469_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u470" class="ax_default _默认样式">
                                        <div id="u470_div" class=""></div>
                                        <div id="u470_text" class="text ">
                                            <p><span>云云协同创新峰会2023</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u471" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u471_div" class=""></div>
                                        <div id="u471_text" class="text ">
                                            <p><span>释放数字生产力</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u472" class="ax_default" data-left="40" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u473" class="ax_default box_2">
                                        <div id="u473_div" class=""></div>
                                        <div id="u473_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u474" class="ax_default _默认样式">
                                        <div id="u474_div" class=""></div>
                                        <div id="u474_text" class="text ">
                                            <p><span>信任中心</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u475" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u475_div" class=""></div>
                                        <div id="u475_text" class="text ">
                                            <p><span>安全、合规、隐私、透明</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u476" class="ax_default" data-left="398" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u477" class="ax_default box_2">
                                        <div id="u477_div" class=""></div>
                                        <div id="u477_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u478" class="ax_default _默认样式">
                                        <div id="u478_div" class=""></div>
                                        <div id="u478_text" class="text ">
                                            <p><span>客户案例</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u479" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u479_div" class=""></div>
                                        <div id="u479_text" class="text ">
                                            <p><span>与您携手完成业务创新</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u480" class="ax_default" data-left="756" data-top="246" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u481" class="ax_default box_2">
                                        <div id="u481_div" class=""></div>
                                        <div id="u481_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u482" class="ax_default _默认样式">
                                        <div id="u482_div" class=""></div>
                                        <div id="u482_text" class="text ">
                                            <p><span>智能驾驶创新峰会</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u483" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u483_div" class=""></div>
                                        <div id="u483_text" class="text ">
                                            <p><span>云上加速 智行万里</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u484" class="ax_default _默认样式">
                                    <div id="u484_div" class=""></div>
                                    <div id="u484_text" class="text ">
                                        <p><span>市场活动</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u485" class="ax_default _默认样式">
                                    <div id="u485_div" class=""></div>
                                    <div id="u485_text" class="text ">
                                        <p><span>全球服务</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Rectangle) -->
                                <div id="u486" class="ax_default _默认样式">
                                    <div id="u486_div" class=""></div>
                                    <div id="u486_text" class="text ">
                                        <p><span>品牌资讯</span></p>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u487" class="ax_default" data-left="398" data-top="344" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u488" class="ax_default box_2">
                                        <div id="u488_div" class=""></div>
                                        <div id="u488_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u489" class="ax_default _默认样式">
                                        <div id="u489_div" class=""></div>
                                        <div id="u489_text" class="text ">
                                            <p><span>分析师报告</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u490" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u490_div" class=""></div>
                                        <div id="u490_text" class="text ">
                                            <p><span>了解权威机构如何评价艾斯云</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Group) -->
                                <div id="u491" class="ax_default" data-left="756" data-top="344" data-width="338"
                                    data-height="88" layer-opacity="1">

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u492" class="ax_default box_2">
                                        <div id="u492_div" class=""></div>
                                        <div id="u492_text" class="text " style="display:none; visibility: hidden">
                                            <p></p>
                                        </div>
                                    </div>

                                    <!-- Unnamed (Rectangle) -->
                                    <div id="u493" class="ax_default _默认样式">
                                        <div id="u493_div" class=""></div>
                                        <div id="u493_text" class="text ">
                                            <p><span>全球创业者峰会</span></p>
                                        </div>
                                    </div>

                                    <!-- MenuText (Rectangle) -->
                                    <div id="u494" class="ax_default _默认样式" data-label="MenuText">
                                        <div id="u494_div" class=""></div>
                                        <div id="u494_text" class="text ">
                                            <p><span>预见创业者的力量</span></p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Unnamed (Image) -->
                                <div id="u495" class="ax_default image">
                                    <img id="u495_img" class="img " src="../../assets/img/home/u495.svg" />
                                    <div id="u495_text" class="text " style="display:none; visibility: hidden">
                                        <p></p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Unnamed (Group) -->
                    <div id="u496" class="ax_default" data-left="0" data-top="16" data-width="1492" data-height="40"
                        layer-opacity="1">

                        <!-- Unnamed (Group) -->
                        <div id="u497" class="ax_default" data-left="1361" data-top="16" data-width="131"
                            data-height="40" layer-opacity="1">

                            <!-- Unnamed (Rectangle) -->
                            <div id="u498" class="ax_default _默认样式">
                                <div id="u498_div" class=""></div>
                                <div id="u498_text" class="text ">
                                    <p><span>使用文档</span></p>
                                </div>
                            </div>

                            <!-- Unnamed (Rectangle) -->
                            <div id="u499" class="ax_default _默认样式">
                                <div id="u499_div" class=""></div>
                                <div id="u499_text" class="text ">
                                    <p><span>控制台</span></p>
                                </div>
                            </div>
                        </div>

                        <!-- Unnamed (Group) -->
                        <div id="u500" class="ax_default" data-left="0" data-top="0" data-width="0" data-height="0"
                            layer-opacity="1">
                        </div>

                        <!-- Unnamed (logo) -->

                        <!-- Unnamed (Group) -->
                        <div id="u502" class="ax_default" data-left="0" data-top="16" data-width="101" data-height="40"
                            layer-opacity="1">

                            <!-- Unnamed (Rectangle) -->
                            <div id="u503" class="ax_default heading_3">
                                <div id="u503_div" class=""></div>
                                <div id="u503_text" class="text ">
                                    <p><span>AI助手</span></p>
                                </div>
                            </div>

                            <!-- Unnamed (Rectangle) -->
                            <div id="u504" class="ax_default box_2">
                                <div id="u504_div" class=""></div>
                                <div id="u504_text" class="text " style="display:none; visibility: hidden">
                                    <p></p>
                                </div>
                            </div>
                        </div>
                        <div id="u501" style="display:none; visibility:hidden;"></div>
                    </div>

                    <!-- 阴影 (Dynamic Panel) -->
                    <div id="u505" class="ax_default" data-label="阴影">
                        <div id="u505_state0" class="panel_state" data-label="State1" style="">
                            <div id="u505_state0_content" class="panel_state_content">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="u142" style="display:none; visibility:hidden;"></div>

        <div id="u506" class="ax_default" data-label="滚动定位">
        </div>
    </div>

</template>
<script lang="ts" setup>
import { onMounted } from 'vue';

var currentState = 0;
function startCarousel() {
    setInterval(() => {
        currentState = (currentState + 1) % 4;
        console.log("currentState: ", currentState);
    }, 3000);
}
onMounted(() => {
    startCarousel();
});
</script>
