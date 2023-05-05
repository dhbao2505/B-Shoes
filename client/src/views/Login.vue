<template>
    <main>
        <div class="login-container">
            <h1 class="h1-login">Đăng nhập</h1>
            <form class="form-login">
                <label for="username" class="label-login">Tên đăng nhập:</label>
                <input class="input-login" type="text" id="username" name="username" required>
                <label for="password" class="label-login">Mật khẩu:</label>
                <input class="input-login" type="password" id="password" name="password" required>
                <button type="submit" class="button-login">Đăng nhập</button>
            </form>
            <a href="#" class="a-login">Quên mật khẩu?</a>
            <p class="p-login">Chưa có tài khoản? <a href="register.html" class="a-login">Đăng ký</a></p>
        </div>
    </main>
</template>