<template>
  <div id="app">
      <el-container>
        <!-- 顶部logo -->
        <el-header>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple-dark">
                <img src="./assets/logo.png" alt="" />
                header
              </div>
            </el-col>
          </el-row>
        </el-header>

        <!-- 问题 -->
        <el-main>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <h4>治疗口臭的办法有哪些</h4>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <p class="date">2020-06-28</p>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <p>
                  近年来，第五代移动通信系统5G已经成为通信业和学术界探讨的热点。5G的发展主要有两个驱动力。一方面以长期演进技术为代表的第四代移动通信系统4G已全面商用，对下一代技术的讨论提上日程；另一方面，移动数据的需求爆炸式增长，现有移动通信系统难以满足未来需求，急需研发新一代5G系统
                </p>
              </div>
            </el-col>
          </el-row>
        </el-main>
        <!-- 医生回答 -->
        <el-main>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <h4>医生回答()</h4>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <el-row>
                  <el-col :span="12">
                    <div class="grid-content bg-purple">
                      <img src="./assets/logo.png" alt="" class="photo" />
                      <div class="grid-content bg-purple person">
                        <h4>刘xx <span class="job">副主任医师</span></h4>
                        <h4 class="perinfo">粉丝：获赞：转发：</h4>
                      </div>
                    </div>
                  </el-col>
                  <el-col :span="12" class="btn">
                    <div class="grid-content bg-purple">
                      <button @click="startHacking">去咨询</button>
                    </div>
                  </el-col>
                </el-row>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <audio src=""></audio>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <h4>
                  近年来，第五代移动通信系统5G已经成为通信业和学术界探讨的热点。5G的发展主要有两个驱动力。一方面以长期演进技术为代表的第四代移动通信系统4G已全面商用，对下一代技术的讨论提上日程；另一方面，移动数据的需求爆炸式增长，现有移动通信系统难以满足未来需求，急需研发新一代5G系统
                </h4>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <p class="date">2020-06-28</p>
              </div>
            </el-col>
          </el-row>
        </el-main>

        <el-main>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <el-row>
                  <el-col :span="12">
                    <div class="grid-content bg-purple">
                      <img src="./assets/logo.png" alt="" class="photo" />
                      <div class="grid-content bg-purple person">
                        <h4>张xx <span class="job">主任医师</span></h4>
                        <h4 class="perinfo">粉丝：获赞：转发：</h4>
                      </div>
                    </div>
                  </el-col>
                  <el-col :span="12" class="btn">
                    <div class="grid-content bg-purple">
                      <button @click="startHacking">去咨询</button>
                    </div>
                  </el-col>
                </el-row>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <video src=""></video>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <h4>
                  近年来，第五代移动通信系统5G已经成为通信业和学术界探讨的热点。5G的发展主要有两个驱动力。一方面以长期演进技术为代表的第四代移动通信系统4G已全面商用，对下一代技术的讨论提上日程；另一方面，移动数据的需求爆炸式增长，现有移动通信系统难以满足未来需求，急需研发新一代5G系统
                </h4>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <p class="date">2020-06-28</p>
              </div>
            </el-col>
          </el-row>
        </el-main>

        <el-main>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <h4>网友回答()</h4>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <el-row>
                  <el-col :span="8">
                    <div class="grid-content bg-purple">
                      <img src="./assets/logo.png" alt="" class="photo" />
                      <div class="grid-content bg-purple person">
                        <h4>网友xxx</h4>
                        <h4 class="perinfo">粉丝：获赞：转发：</h4>
                      </div>
                    </div>
                  </el-col>
                </el-row>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <h4>
                  近年来，第五代移动通信系统5G已经成为通信业和学术界探讨的热点。5G的发展主要有两个驱动力。一方面以长期演进技术为代表的第四代移动通信系统4G已全面商用，对下一代技术的讨论提上日程；另一方面，移动数据的需求爆炸式增长，现有移动通信系统难以满足未来需求，急需研发新一代5G系统
                </h4>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <p class="date">2020-06-28</p>
              </div>
            </el-col>
          </el-row>
        </el-main>
        <el-main>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <el-row>
                  <el-col :span="8">
                    <div class="grid-content bg-purple">
                      <img src="./assets/logo.png" alt="" class="photo" />
                      <div class="grid-content bg-purple person">
                        <h4>网友xxx</h4>
                        <h4 class="perinfo">粉丝：获赞：转发：</h4>
                      </div>
                    </div>
                  </el-col>
                </el-row>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <h4>
                  近年来，第五代移动通信系统5G已经成为通信业和学术界探讨的热点。5G的发展主要有两个驱动力。一方面以长期演进技术为代表的第四代移动通信系统4G已全面商用，对下一代技术的讨论提上日程；另一方面，移动数据的需求爆炸式增长，现有移动通信系统难以满足未来需求，急需研发新一代5G系统
                </h4>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <p class="date">2020-06-28</p>
              </div>
            </el-col>
          </el-row>
        </el-main>
        <el-main>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <el-row>
                  <el-col :span="8">
                    <div class="grid-content bg-purple">
                      <img src="./assets/logo.png" alt="" class="photo" />
                      <div class="grid-content bg-purple person">
                        <h4>网友xxx</h4>
                        <h4 class="perinfo">粉丝：获赞：转发：</h4>
                      </div>
                    </div>
                  </el-col>
                </el-row>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <h4>
                  近年来，第五代移动通信系统5G已经成为通信业和学术界探讨的热点。5G的发展主要有两个驱动力。一方面以长期演进技术为代表的第四代移动通信系统4G已全面商用，对下一代技术的讨论提上日程；另一方面，移动数据的需求爆炸式增长，现有移动通信系统难以满足未来需求，急需研发新一代5G系统
                </h4>
              </div>
            </el-col>
          </el-row>
          <el-row>
            <el-col :span="24">
              <div class="grid-content bg-purple">
                <p class="date">2020-06-28</p>
              </div>
            </el-col>
          </el-row>
        </el-main>
        <el-footer>
          <el-row>
            <el-col :span="24">
              <div class="grid-content">
                <h4>xxxx医院@2020版权所有</h4>
                <h4>网站备案号：xxxxxxxxxxx</h4>
              </div>
            </el-col>
          </el-row>
        </el-footer>
        <div class="noinfo"></div>
      </el-container>
      <!-- 一键复制 -->
          <el-row class="bottomBar">
            <el-col :span="24">
              <div class="grid-content">
                <el-row>
                  <el-col :span="12" height="50px">
                    <div class="grid-content"  display="block">
                      <img src="./assets/logo.png" alt="" class="photo" />
                      <div class="grid-content person">
                        <h6>微信</h6>
                        <h6 class="perinfo">李和平<span color="gray" class="hao">liheping</span></h6>
                      </div>
                    </div>
                  </el-col>
                  <el-col :span="12" class="btn" height="50px">
                    <div class="grid-content">
                      <input @click="copy" display="block" type="button" value="一键复制微信号">
                    </div>
                  </el-col>
                </el-row>
              </div>
            </el-col>
          </el-row>
    </div>
</template>

<script>
export default {
  methods: {
    startHacking() {
      this.$notify({
        title: "Hello!",
        type: "success",
        message:
          "去咨询微信号：liheping",
        duration: 5000,
      });
    },
    copy(e) {
    let transfer = document.createElement('input');
    document.body.appendChild(transfer);
    transfer.value = document.getElementsByClassName('hao')[0].innerHTML;  // 这里表示想要复制的内容
    transfer.focus();
    transfer.select();
    if (document.execCommand('copy')) {
        document.execCommand('copy');
    }
    transfer.blur();
    alert('复制成功');
    document.body.removeChild(transfer);
}

  },
};
</script>

<style>
</style>
