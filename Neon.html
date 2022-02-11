let canvas = document.querySelector('canvas');
let ctx = canvas.getContext('2d');
let objs = [];
let color = [
    '#34343F',
    '#FFF',
    '#F991B3',
    '#FFCF31',
    '#31B9FF',
    '#DB5252'
];

canvas.width = window.innerWidth;
canvas.height = window.innerHeight;

window.addEventListener('resize', function(){
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
}, false);

function Cubo(y, vy){
    this.size = Math.floor(10 + Math.random() * 50);
	this.w = this.size;
    this.h = this.size;
    this.x = Math.random() * (innerWidth - this.w * 2) + this.w;
    this.y = y;
    this.vy = vy;
    this.rot = 0;
    this.vel = 1;
    this.line = Math.floor(0.25 + Math.random() * 20);
    this.color = color[(Math.floor(Math.random() * color.length))];
    
    this.draw = function(){
    	ctx.save();
        ctx.lineWidth = this.line;
        ctx.strokeStyle = this.color;
        ctx.translate(this.x + this.w / 2, this.y + this.h / 2);
        ctx.rotate(this.rot);
        ctx.strokeRect(-this.w / 2, -this.h / 2, this.w, this.h);
        ctx.stroke();
        ctx.restore();
    }
    
    
    this.update = function(){
    	this.rot += Math.PI / 180 * this.vel;
        
        if(this.y + (this.h * 2) < 0){
            this.y = innerHeight + this.h;
            this.y -= this.vy;
        }
        
        this.y -= this.vy;
        this.draw();
    }
}

function mult(){
    objs = [];
    for(var i = 0; i < 20; i++){
        var y = 100;
        var vy = (Math.random() + 1);
        objs.push(new Cubo(y, vy));
    }
}

function init(){
    requestAnimationFrame(init);
    ctx.clearRect(0, 0, innerWidth, innerHeight);
    
    for(var i in objs){
        var obj = objs[i];
        obj.update();
    }
    
}
mult();
init();
