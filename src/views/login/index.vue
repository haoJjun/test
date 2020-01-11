<template>
    <div class="login">
        <!-- element -->
        <!-- 卡片组件 -->
        <el-card class="login-card">
            <!-- 卡片内容 -->
            <div class="title">
                <img src="../../assets/img/logo_index.png" alt="">
            </div>
            <!-- 表单 -->
            <el-form style="margin-top:30px">
                <el-form-item >
                    <!-- 手机号 -->
                    <el-input></el-input>
                </el-form-item>
                <el-form-item >
                    <!-- 验证码 -->
                    <el-input style="width:280px"></el-input>
                    <!-- 按钮 -->
                    <el-button plain style="float:right">发送验证码</el-button>
                </el-form-item>
                <el-form-item>
                    <!-- 勾选同意框 -->
                    <el-checkbox>我已阅读并同意协议</el-checkbox>
                </el-form-item>
                <el-form-item>
                    <el-button type="primary" style="width:100%">登录</el-button>
                </el-form-item>
            </el-form>
        </el-card>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.login {
    background: url('../../assets/img/login_bg.jpg');
    background-size: cover;
    height:100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    .login-card {
        width:440px ;
        height: 360px;
        .title {
            text-align: center;
            img {
                height: 45px;
            }
        }
    }
}
</style>
>
