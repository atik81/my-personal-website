*{
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
  box-sizing: border-box;
}
body{
  background: #080808;
  color: #fff;
}
#header{
  width: 100%;
  height: 100vh;
  background-image: url(image/bac.png);
  background-size: cover;
  background-position: center;

}

.container{
  padding: 10px 10%;
}
nav{
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}
.logo{
  width:  300px;

}
nav ul li{
  display: inline-block;
  list-style: none;
  margin: 10px 20px;
}
nav ul li a{
  color: #fff;
  text-decoration: none;
  font-size: 18px;
  position: relative;
}
nav ul li a::after{
  content: '';
  width: 0;
  height: 3px;
  background: #4206d8;
  position: absolute;
  left: 0;
  bottom: -6px;
  transition: 0.5s;
}
nav ul li a:hover::after{
  width: 100%;
}
.header-text{
  margin-top: 20%;
  font-size: 30px;
}
.header-text h1{
  font-size: 60px;
  margin-top: 20px;
}
.header-text h1 span{
  color: #4206d8;

}
