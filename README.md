
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Asmita</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Bodoni+Moda:ital@1&display=swap');
*{
    padding: 0;
    margin: 0;
    font-family: 'Bodoni Moda', serif;
}
body{
    width: 70px;;
    background-image: url("PicsArt_03-19-10.48.19.jpg");
    background-repeat: no-repeat;
  background-size: 1300px 800px;
}
.container{
    perspective: 1000px;
}
.card{
    width: 280px;
    height: 360px;
    position: absolute;
    top: 100px;
    left: 230px;
    transition: 2s;
    transform-style: preserve-3d;
}
.card:hover{
    transform: rotateY(180deg);
}
.block{
    position: absolute;
    top:200px;
    right: 600px;
    perspective: 800px;
}
.outside,.inside{
    width: 100%;
    height: 100%;
    border-radius: 20px;
    text-align: center;
    padding: 1.5rem;
}
.outside{
    background-color: blanchedalmond;
    box-shadow: inset 0 5px 10px rgba(0,0,0,0.5);
    position: absolute;
    backface-visibility: hidden;
}
.outside h1{
    font-size: 3rem;
    font-weight: bold;
    color: salmon;
    margin-bottom: 30px;
}
.inside{
    background-color: rgb(206, 198, 187);
    box-shadow: inset 0 5px 10px rgba(0,0,0,0.5);
    transform: rotateY(180deg);
    backface-visibility: hidden;
}
.inside h3{
    font-size: 1.2rem;
    font-weight: bold;
    margin-top: 20px;
    
}
.frames{
    width: 400px;
    height: 150px;
    box-shadow: 0 5px 10px rgba(255, 255, 255, 0.5);
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding: 0 0.8rem;

    transform: rotateY(-230deg) rotateX(20deg);
    position: absolute;
}
.frames img{
    width: 125px;
    height: 125px;
    border-radius: 50%;
    box-shadow: 0 5px 10px rgba(0,0,0,0.5);
}
.frames p{
   font-size: 20px;
   font-weight: bold;
   transform: rotateY(180deg);
}
.frames:nth-child(1)
{
    top:-110px;
    z-index: -1;
    background-color: coral;
}
.frames:nth-child(2){
    background-color: goldenrod;
}
.frames:nth-child(3)
{
    top:100px;
    background-color: burlywood;
}
    </style>
</head>
<body>
    <div class="container">
        <div class="card">
            <div class="outside">
                <h1>Happy Birthday</h1>
                <h3>to the prettiest girl in the universe.</h3>
            </div>
            <div class="inside">
               

              >
                <h3>I Love You...
                </h3><br>
                
            </div>
        </div>

        

    </div>
</body>
</html>
