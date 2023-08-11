<script>
  import loginBackground from '../../public/assets/loginBackground.gif';
</script>


<div class="content">
    <img src={ loginBackground } alt='background'/>
    <span class="center-container">
      <p class="text">Welcome</p>
      <form action="#">
        <div class="field">
          <span class="fa fa-user"></span>
          <input type="username" placeholder="User Name" required>
        </div>
          <div class="field">
            <span class="fa fa-lock"></span>
            <input type="password" placeholder="Password" required>
          </div>
        <button>Log in</button>
      </form>
    </span>
</div>

<style>
.content{
  width: 45em; 
  border-radius: 10px;
  padding: 40px 30px;
  box-shadow: -3px -3px 9px #aaa9a9a2, 3px 3px 7px rgba(147, 149, 151, 0.671);
  height: 400px;
  margin-bottom: 6em;
}

.center-container {
  text-align: center;
}

.content img {
  border-radius: 10px;
  margin: -40px -30px;
  position: absolute;
  width: 100%;
  height: 400px;
  object-fit: cover;

  animation-name: hue;
  animation-iteration-count: infinite;  
  animation-duration: 10s; 
  
}

@keyframes hue {  
  0% { filter: hue-rotate(360deg) blur(6px); }
  25% { filter: hue-rotate(320deg) blur(4px); }
  50% { filter: hue-rotate(280deg) blur(1px); }
  75% { filter: hue-rotate(320deg) blur(4px); }
  100% { filter: hue-rotate(360deg) blur(6px); }
}

.content p{
  position: relative;
  font-size: 26px;
  font-weight: 600;
  margin-bottom: 35px;
  color: rgb(247, 233, 233);
}

.field{
  height: 50px;
  width: 100%;
  display: flex;
  position: relative;
}

.field input{
  height: 100%;
  width: 100%;
  padding-left: 45px;
  font-size: 18px;
  outline: none;
  border: none;
  color: #fff;
  border: 2px solid rgba(255, 255, 255, 0.438);
  box-shadow: -3px -3px 9px #aaa9a9a2, 2px 2px 4px rgba(147, 149, 151, 0.671);
  border-radius: 8px;
  background: rgba(105, 105, 105, 0);
}

.field input::placeholder{
  color: #fff;
}

.field:nth-child(2){
  margin-top: 20px;
}

.field span{
  position: absolute;
  width: 50px;
  line-height: 50px;
  color: #ffffff;
  text-align:center;
}

.content button {
  margin: 25px 0 0 0;
  padding: 8px 20px;
  width: fit-content;
  height: 50px;
  color: #fff;
  font-size: 18px;
  font-weight: 600;
  border: 2px solid rgba(255, 255, 255, 0.438);
  box-shadow: -3px -3px 9px #aaa9a9a2, 2px 2px 4px rgba(147, 149, 151, 0.671);
  border-radius: 8px;
  background: rgba(105, 105, 105, 0);
  margin-top: 40px;
  outline: none;
  cursor: pointer;
  border-radius: 8px;
  position: relative;
}
</style>