# New-Project-
This is a crate  for education only 
Html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      *{
    margin: 0;
    padding: 0;
}

body{
    background-color: #000;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.card{
    background: linear-gradient(45deg, #a5fecb,#20bdff);
    height: 400px;
    width: 400px;
    border-radius: 50%;
    transform-style: preserve-3d;
    transition: all 1s ease-in-out;
}

.circle{
    background: linear-gradient(#ffffff27, #ffffff28);
    border-radius: inherit;
    position: absolute;
    box-shadow: -5px 5px 10px #64646433;
    transition: all 1s ease-in-out;
}

.circle:nth-child(1) {
    inset: 25px;
    transition-delay: 0.1s;
}

.circle:nth-child(2) {
    inset: 50px;
    transition-delay: 0.2s;
}

.circle:nth-child(3) {
    inset: 75px;
    transition-delay: 0.3s;
}

.circle:nth-child(4) {
    inset: 100px;
    transition-delay: 0.4s;
}

.circle:nth-child(5) {
    inset: 125px;
    transition-delay: 0.5s;
}

/*hover effect*/

.card:hover{
    transform: rotate3d(1,1,0, 60deg);
}

.card:hover .circle:nth-child(1) {
    transform: translate3d(0, 0 , 30px);
}

.card:hover .circle:nth-child(2) {
    transform: translate3d(0, 0 , 60px);
}

.card:hover .circle:nth-child(3) {
    transform: translate3d(0, 0 , 90px);
}

.card:hover .circle:nth-child(4) {
    transform: translate3d(0, 0 , 120px);
}

.card:hover .circle:nth-child(5) {
    transform: translate3d(0, 0 , 150px);
}
    </style>
</head>
<body>
    <div class="card">
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
        <div class="circle"></div>
    </div>
</body>
</html>

