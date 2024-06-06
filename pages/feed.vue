<template>
  <div class="sign">
    <left-sidebad></left-sidebad>
    <div class="signin_box">
      <div class="signin">
        <div class="continue_sign">
          <div class="youtoube_sign">
            <svg
              width="48"
              height="48"
              viewBox="0 0 48 48"
              aria-hidden="true"
              jsname="jjf7Ff"
            >
              <path
                fill="#4285F4"
                d="M45.12 24.5c0-1.56-.14-3.06-.4-4.5H24v8.51h11.84c-.51 2.75-2.06 5.08-4.39 6.64v5.52h7.11c4.16-3.83 6.56-9.47 6.56-16.17z"
              ></path>
              <path
                fill="#34A853"
                d="M24 46c5.94 0 10.92-1.97 14.56-5.33l-7.11-5.52c-1.97 1.32-4.49 2.1-7.45 2.1-5.73 0-10.58-3.87-12.31-9.07H4.34v5.7C7.96 41.07 15.4 46 24 46z"
              ></path>
              <path
                fill="#FBBC05"
                d="M11.69 28.18C11.25 26.86 11 25.45 11 24s.25-2.86.69-4.18v-5.7H4.34C2.85 17.09 2 20.45 2 24c0 3.55.85 6.91 2.34 9.88l7.35-5.7z"
              ></path>
              <path
                fill="#EA4335"
                d="M24 10.75c3.23 0 6.13 1.11 8.41 3.29l6.31-6.31C34.91 4.18 29.93 2 24 2 15.4 2 7.96 6.93 4.34 14.12l7.35 5.7c1.73-5.2 6.58-9.07 12.31-9.07z"
              ></path>
              <path fill="none" d="M2 2h44v44H2z"></path>
            </svg>
            <h1>Sign in</h1>
            <p>to continue to YouTube</p>
          </div>

          <div class="g-input">
            <input
              type="text"
              id="user-name"
              name="user-name"
              placeholder=" "
            />
            <label for="user-name">Email</label>
          </div>
          <div class="g-input">
            <input
              type="password"
              id="password"
              name="password"
              placeholder=" "
            />
            <label for="password">Password</label>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style>
.sign {
  display: flex;
  box-sizing: border-box;
  width: 100%;
  height: 91vh;
  background: rgb(239, 246, 250);
}

.signin_box {
  display: flex;
  justify-content: center;
  align-items: center;
  max-width: 1200px;
  margin: auto;
  height: 91vh;
}

.signin {
  display: flex;
  width: 750px;
  height: 350px;
  border-radius: 22px;
  background: #ffff;
}

.signin svg {
  margin: 33px;
}

.continue_sign {
  margin: 33px;
}
.continue_sign h1 {
  color: #000;
  font-size: 28px;
  margin-left: 33px;
}
.continue_sign p {
  color: #000;
  font-size: 16px;
  margin: 29px;
}

/*  */

.continue_sign {
  margin-left: 55px;
}

.g-input {
  position: relative;
  margin-bottom: 10px;
  box-sizing: border-box;
  display: flex;
}

.g-input label {
  background: white;
  padding: 3px;
  font-size: 12px;
  transition: transform 150ms cubic-bezier(0.4, 0, 0.2, 1),
    opacity 150ms cubic-bezier(0.4, 0, 0.2, 1);
  transform-origin: bottom left;
  color: #110f0f;
  font-family: arial;
  position: absolute;
  top: 7px;
  left: 7px;
  z-index: 1;
  cursor: text;
}

.g-input input,
.g-input textarea {
  border: 1px solid #131111;
  display: block;
  padding: 10px;
  border-radius: 3px;
  width: 100%;
  box-sizing: border-box;
}

.g-input.fill {
  display: block;
  width: 100%;
}

.g-input input:focus,
.g-input textarea:focus {
  outline: 0;
  border-color: #0d60cc;
}

.g-input input:focus + label,
.g-input input:not(:placeholder-shown) + label,
.g-input textarea:focus + label,
.g-input textarea:not(:placeholder-shown) + label {
  transform: translateX(-3px) translateY(-15px);
  font-size: 10px;
  color: #0b61d1;
}
</style>
