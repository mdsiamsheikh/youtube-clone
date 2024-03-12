<template>
  <div class="popup_header">
    <div class="popup_content">
      <img
        id="img"
        draggable="false"
        class="style-scope yt-img-shadow"
        alt=""
        height="40"
        width="40"
        src="https://yt3.ggpht.com/r0OHzZ05dh4t4UBiBDkL28Vr1AK8q7vIGH9LeOeReP_lyE9zuXAfOzJtfCQmQzDfP1B25TK_Nw=s108-c-k-c0x00ffffff-no-rj"
      />
      <div class="popup-img">
        <p>Siam Sheikh</p>
        <p>@SiamSheikh-fd7bj</p>
        <a href="#">View your channel</a>
      </div>
    </div>
    <hr class="hr" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.popup_header {
  width: 300px;
  height: 50vh;
  font-family: "Roboto", sans-serif;
  margin-top: 2px;
  border-radius: 5px;
}

img {
  border-radius: 50%;
}

.popup_content {
  display: flex;
  align-items: center;
  margin-left: 15px;
}

.popup-img {
  margin-left: 15px;
  margin-top: 10px;
}

.popup-img p {
  margin: 4px;
  font-size: 16px;
  font-weight: 400;

  line-height: 22px;
  color: rgb(15, 15, 15);
}

.popup-img a {
  text-decoration: none;
  color: #007bff;
  font-size: 14px;
  font-weight: 400;
  line-height: 20px;
}

.hr {
  margin-top: 20px;
}
</style>
