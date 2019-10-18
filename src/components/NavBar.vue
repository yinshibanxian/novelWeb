<template>
    <div class="nav-bar">
        <div class="username">
            <label for="username">用户名：</label>
            <input type="text" name="username" style="height: 15px;width: 100px" v-model="username">
        </div>
        
        <div class="password">
            <label for="password">密码：</label>
            <input type="password" name="password" style="height: 15px;width: 100px" v-model="password">
        </div>

        <div class="login-btn-wrapper">
            <button>登 陆</button>
        </div>

        <div class="sign-btn-wrapper">
            <button>注 册</button>
        </div>
      
    </div>
</template>

<script>
export default {
    data(){
        return {
            username: '',
            password: ''
        }
    }
}
</script>
<style scoped lang="scss" type="text/css">
.nav-bar {
    width: 100%;
    height: 29px;
    border-bottom: 1px solid #EDEDED;
    background: #F1F3F3;
    font-size: 10px;
    color: #170E45;
    .username {
        padding-left: 900px;
        padding-top: 5px;
        display: inline-block;
    }
    .password {
        display: inline-block;
        padding-top: 5px;
        margin-left: 15px;
    }

    .login-btn-wrapper {
        display: inline-block;
        margin-left: 15px;
    }
    .sign-btn-wrapper {
        display: inline-block;
        margin-left: 15px;
    }
}
</style>
