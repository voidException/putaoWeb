<template>
  <div style="background-color: #F0F0F0">
      <!--发现头部-->
      <div class="header">
        <div class="headerLeft">
            <img src="../../assets/imgs/faxianPublic.png" class="headerImg">
            <div>互助人员公示</div>
        </div>
        <div class="rosterPublic">名单公示</div>
      </div>
      <!--发现，中间部分-->
      <div class="inviteFriendContain">
        <div class="inviteLeft">
          <div  class="inviteLeft1">喊亲友来加入方舟互助</div>
          <div  class="inviteLeft2" >每邀请一人</div>
          <div  class="inviteLeft2">即可获得5元奖励</div>
          <div  class="inviteLeft3">我的奖励 >></div>
        </div>
        <div class="inviteRight">
          <img src="../../assets/imgs/feiren.png" class="inviteRightImg">
        </div>
      </div>
      <!--邀请亲朋好友加入-->
      <div class="yaoqingContain">
          <div class="yaoqingWrapper">
              <div class="yaoqingView">邀请亲朋好友加入</div>
          </div>
          <div class="pageBottom">
              <img src="../../assets/imgs/weibo@2x.png" class="weixin">
              <img src="../../assets/imgs/pengyouquan@2x.png" class="weixin">
              <img src="../../assets/imgs/qq@2x.png" class="weixin">
              <img src="../../assets/imgs/kongjian@2x.png" class="weixin">
          </div>
          <div  class="ruleWrapper">规则说明 >></div>
      </div>
  </div>
</template>

<script>
  import mHeader from '../../components/header'

  export default {
    name: 'broadcast',
    components: {
      mHeader
    }
  }
</script>
<style>
  .header{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    height: 80px;
    background-color: #F0F0F0;
    padding-left: 12px;
    padding-right: 12px;
  }
  .headerLeft{
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
  }
  .headerImg{
    width: 30px;
    height: 30px;
    margin-right: 3px;
  }
  .rosterPublic{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    height: 30px;
    border-radius:15px;
    width: 80px;
    border: solid  #0093EC 1px;
    color: #0093EC;
  }
  .inviteFriendContain{
    display: flex;
    flex-direction:row;
    align-items:center;
    justify-content:space-between;
    height:210px;
    background-color:#fff
  }
  .inviteLeft{
    width:60%;
    flex-direction:column;
    justify-content:center;
    align-items:flex-start;
    padding-left:12px
  }
  .inviteLeft1{
      color:#4c4c4b;
      margin-bottom:10px;
      font-size:16px
   }
  .inviteLeft2{
    font-size:22px;
    color:#FF6D00;
    font-weight:bold
   }
   .inviteLeft3{
     font-size:12px;
     color:#0093EC;
     margin-top:12px
   }
  .inviteRight{
    width: 38%;
    height: 100px;
  }
  .inviteRightImg{
    height: 130px;
    width: 140px;
  }
  .yaoqingContain{
    display: flex;
    margin-top: 1px;
    background-color:#fff;
    height:220px;
    flex-direction:column;
    justify-content:center
  }
  .yaoqingWrapper{
     display: flex;
     flex-direction:row;
     width:100%;
     height: 52px;
     align-items: center;
     justify-content:center;
  }
  .yaoqingView{
    display: flex;
    width:80%;
    background-color:#0093EC;
    height:40px;
    align-items:center;
    justify-content:center;
    border-radius:30px;
    color: #ffffff;
  }
  .weixin{
    width:50px;
    height:50px;
    border-radius:25px
  }
  .pageBottom{
    display: flex;
    flex-direction:row;
    align-items:center;
    justify-content:space-around;
    height:80px;
  }
  .ruleWrapper{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    color: #008DF0;
  }
</style>
