<div class="content">
    <p class=”text”>Login</p>
    <form action="#">
        <div class="field">
            <span class="fa fa-user"></span>
            <input type="username" placeholder="User Name" required>
        </div>
        <div class="field">
            <span class="fa fa-lock"></span>
            <input type="password" placeholder="Password">
        </div>
    </form>
</div>

<style>
.content{
    width: 45em; 
    border-radius: 10px;
    padding: 40px 30px;
    box-shadow: -3px -3px 9px #aaa9a9a2,
                3px 3px 7px rgba(147, 149, 151, 0.671); 
}

.content p{
    text-align: center;
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
  color: #e0d2d2;
  border: 1px solid rgba(255, 255, 255, 0.438);
  border-radius: 8px;
  background: rgba(105, 105, 105, 0);
}

.field input::placeholder{
  color: #e0d2d2a6;
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
</style>