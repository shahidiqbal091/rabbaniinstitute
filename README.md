<!-- Login Modal -->
<div class="modal" id="loginModal">
    <div class="modal-content">
        <span class="close-modal">&times;</span>
        <h2>Student Login</h2>
        <form id="loginForm">
            <div class="form-group">
                <label for="loginEmail">Email</label>
                <input type="email" id="loginEmail" name="email" required>
            </div>
            <div class="form-group">
                <label for="loginPassword">Password</label>
                <input type="password" id="loginPassword" name="password" required>
            </div>
            <div class="form-group">
                <button type="submit" class="btn">Login</button>
            </div>
            <div class="form-footer">
                <p>Don't have an account? <a href="#" id="showRegister">Register</a></p>
                <p><a href="#" id="forgotPassword">Forgot Password?</a></p>
            </div>
        </form>
    </div>
</div>

<!-- Registration Modal -->
<div class="modal" id="registerModal">
    <div class="modal-content">
        <span class="close-modal">&times;</span>
        <h2>Create Account</h2>
        <form id="registerForm">
            <div class="form-group">
                <label for="regName">Full Name</label>
                <input type="text" id="regName" name="name" required>
            </div>
            <div class="form-group">
                <label for="regEmail">Email</label>
                <input type="email" id="regEmail" name="email" required>
            </div>
            <div class="form-group">
                <label for="regPhone">Phone Number</label>
                <input type="tel" id="regPhone" name="phone" required>
            </div>
            <div class="form-group">
                <label for="regPassword">Password</label>
                <input type="password" id="regPassword" name="password" required>
            </div>
            <div class="form-group">
                <label for="regConfirmPassword">Confirm Password</label>
                <input type="password" id="regConfirmPassword" name="confirmPassword" required>
            </div>
            <div class="form-group">
                <button type="submit" class="btn">Register</button>
            </div>
            <div class="form-footer">
                <p>Already have an account? <a href="#" id="showLogin">Login</a></p>
            </div>
        </form>
    </div>
</div>

<!-- Dashboard Link (shown after login) -->
<div id="userMenu" style="display: none;">
    <a href="dashboard.html" class="btn">My Dashboard</a>
    <button id="logoutBtn" class="btn btn-outline">Logout</button>
</div>
