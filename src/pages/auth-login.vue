<template lang="id">
    <div id="auth">
        <div class="row p-4">
            <div class="col-lg-5 card mt-5 p-4">
                <div class="card-content">
                    <div class="auth-logo mb-5 text-center">
                        <a href="#"><img src="assets/images/logo/logo.png" class="img-fluid" alt="Logo"></a>
                    </div>
                    <h3 class="auth-title">Log in.</h3>

                    <form action="index.html">
                        <div class="form-group position-relative has-icon-left mb-4 mt-4">
                            <input type="text" class="form-control form-control-lg" placeholder="Username">
                            <div class="form-control-icon">
                                <i class="bi bi-person"></i>
                            </div>
                        </div>
                        <div class="form-group position-relative has-icon-left mb-4">
                            <input type="password" class="form-control form-control-lg" placeholder="Password">
                            <div class="form-control-icon">
                                <i class="bi bi-shield-lock"></i>
                            </div>
                        </div>
                        <div class="form-check form-check-lg d-flex align-items-end">
                            <input class="form-check-input me-2" type="checkbox" value="" id="flexCheckDefault">
                            <label class="form-check-label text-gray-600" for="flexCheckDefault">
                                Keep me logged in
                            </label>
                        </div>
                        <button class="btn btn-primary btn-block btn-lg shadow-lg mt-3 fs-6">Log in</button>
                    </form>
                    <div class="text-center mt-3 text-lg fs-6">
                        <p><a class="font-bold" href="auth-forgot-password.html">Forgot password?</a>.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'login',
}
</script>

<style>
    .col-lg-5 {
        margin: auto;
    }
    #auth {
        background-color: #F2F7FF;
    }
</style>
