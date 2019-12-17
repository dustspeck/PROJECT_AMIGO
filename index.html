<!DOCTYPE html>
<html>
<head>
	<title>Amigo</title>
	<script type="text/javascript" src="./pixi-legacy.min.js"></script>
	<script type="text/javascript" src="./pixi-sound.js"></script>
	<!-- <script type="text/javascript" src="./webfont.js"></script> -->
</head>
<body>
	<script>
		const app = new PIXI.Application({
			autoResize: true,
  			resolution: devicePixelRatio 
		});
		var renderer = PIXI.autoDetectRenderer(window.innerWidth-15,window.innerHeight-20,{
			transparent:true
			//backgroundColor : 0x45095f
		});
		var H = window.innerHeight;
		var W = window.innerWidth;
		var xOff = W/2;
		var yOff = H/2;

		var stage = new PIXI.Container();

		var char_body = PIXI.Texture.from('assets/amigo/body.png');
		var char_shadow = PIXI.Texture.from('assets/amigo/shadow.png');
		var char_eyes = PIXI.Texture.from('assets/amigo/f_eyes.png');
		var char_eyes_r = PIXI.Texture.from('assets/amigo/f_eyes_r.png');
		var char_eyes_l = PIXI.Texture.from('assets/amigo/f_eyes_l.png');
		var char_sad = PIXI.Texture.from('assets/amigo/f_sad.png');
		var char_mouth = PIXI.Texture.from('assets/amigo/f_mouth.png');
		var char_mouth1 = PIXI.Texture.from('assets/amigo/f_mouth1.png');
		var char_smile = PIXI.Texture.from('assets/amigo/f_smile.png');
		var char_smile1 = PIXI.Texture.from('assets/amigo/f_smile1.png');
		var char_sad = PIXI.Texture.from('assets/amigo/f_sad.png');
		var char_tearyeyes = PIXI.Texture.from('assets/amigo/f_tearyeyes.png');
		var char_tearyeyes1 = PIXI.Texture.from('assets/amigo/f_tearyeyes1.png');
		var char_wavymouth = PIXI.Texture.from('assets/amigo/f_wavymouth.png');
		var char_wavymouth1 = PIXI.Texture.from('assets/amigo/f_wavymouth1.png');
		var char_closedeyes = PIXI.Texture.from('assets/amigo/f_closedeyes.png');
		var char_closedeyes1 = PIXI.Texture.from('assets/amigo/f_closedeyes1.png');		
		var char_blush = PIXI.Texture.from('assets/amigo/f_blushbody.png');
		var char_halfopeneyes = PIXI.Texture.from('assets/amigo/f_halfopeneyes.png');
		var char_blink0 = PIXI.Texture.from('assets/amigo/f_blink0.png');
		var char_blink1 = PIXI.Texture.from('assets/amigo/f_blink1.png');
		var char_blink2 = PIXI.Texture.from('assets/amigo/f_blink2.png');
		var char_blink3 = PIXI.Texture.from('assets/amigo/f_blink3.png');

		var t_room1 = PIXI.Texture.from('assets/rooms/bg-room1.jpg');
		var t_room2 = PIXI.Texture.from('assets/rooms/bg-room2.jpg');
		var t_room3 = PIXI.Texture.from('assets/rooms/bg-room3.jpg');
		var t_room4 = PIXI.Texture.from('assets/rooms/bg-room4.jpg');
		var t_arr_rt = PIXI.Texture.from('assets/objects/arr_rt.png');
		var t_arr_lt = PIXI.Texture.from('assets/objects/arr_lt.png');
		var t_balloon0 = PIXI.Texture.from('assets/objects/f_balloon0.png')
		var t_balloon1 = PIXI.Texture.from('assets/objects/f_balloon1.png')
		var t_heart = PIXI.Texture.from('assets/objects/heart.png');
		var h_bar0 = PIXI.Texture.from('assets/objects/h_bar0.png');
		var h_bar1 = PIXI.Texture.from('assets/objects/h_bar1.png');
		var h_bar2 = PIXI.Texture.from('assets/objects/h_bar2.png');
		var h_bar3 = PIXI.Texture.from('assets/objects/h_bar3.png');
		var h_bar4 = PIXI.Texture.from('assets/objects/h_bar4.png');
		var h_bar5 = PIXI.Texture.from('assets/objects/h_bar5.png');
		var t_food0 = PIXI.Texture.from('assets/objects/food0.png');

		var room = new PIXI.Sprite(t_room1);
		var body = new PIXI.Sprite(char_body);
		var shadow = new PIXI.Sprite(char_shadow);
		var eyes = new PIXI.Sprite(char_eyes);
		var mouth = new PIXI.Sprite(char_mouth);
		
		var arr_rt = new PIXI.Sprite(t_arr_rt);
		var arr_lt = new PIXI.Sprite(t_arr_lt);
		var balloon0 = new PIXI.Sprite(t_balloon0);

		var amigo = [body, eyes, mouth];
		var amigo_health = 1;

		var arr_health = [h_bar0, h_bar1, h_bar2, h_bar3, h_bar4, h_bar5];
		var arr_mood = ['fsad', 'sad', 'smile', 'cutesmile', 'laugh', 'fhappy'];
		var mood_v = 0;
		var mood=arr_mood[mood_v];
		var arrt_rooms = [t_room1, t_room2, t_room3, t_room4];

		//add BG
		room.position.set(0,0);
		room.height = H;
		room.width = W;
		stage.addChild(room);

		/*add frontend*/

		//arrow right
		arr_rt.width = W/10;
		arr_rt.height = W/10;
		arr_rt.position.set(W - arr_rt.width - 30, H/2);
		stage.addChild(arr_rt);
		arr_rt.interactive = true;
		//arrow left
		arr_lt.width = W/10;
		arr_lt.height = W/10;
		arr_lt.position.set(30, H/2);
		stage.addChild(arr_lt);
		arr_lt.interactive = true;
		arr_lt.visible=false;
		//health bar
		var heart = new PIXI.Sprite(t_heart);
		heart.height = W/10;
		heart.width = heart.height;
		heart.position.set(10, 10);
		stage.addChild(heart);
		var hbar = new PIXI.Sprite(h_bar1);
		hbar.width = W/2;
		hbar.height = hbar.width/8;
		hbar.position.set(heart.position.x + heart.width + 20, heart.position.y + (heart.height-hbar.height)/2);
		stage.addChild(hbar);
		
		//add char shadow
		shadow.width = 0.75 * W;
		shadow.height = 0.5 * shadow.width;
		shadow.position.set(xOff - (shadow.width/2), (1.2*yOff)+(0.33*W/2));
		stage.addChild(shadow);

		//add char
		body.height = 0.33 * W;
		body.width = body.height;
		body.position.set(xOff - (body.width/2), 1.2*yOff);
		stage.addChild(body);
		body.interactive = true;

		//add eyes
		eyes.height = 0.33 * W;
		eyes.width = eyes.height;
		eyes.position.set(xOff - (eyes.width/2), 1.2*yOff);
		stage.addChild(eyes);

		//add mouth
		mouth.height = 0.33 * W;
		mouth.width = mouth.height;
		mouth.position.set(xOff - (mouth.width/2), 1.2*yOff);
		stage.addChild(mouth);

		//add food
		var food0 = new PIXI.Sprite(t_food0);
		food0.height = W/5;
		food0.width = food0.height;
		food0.position.set( xOff-(food0.width/2), H - food0.height - 40);
		stage.addChild(food0);
		food0.interactive = true;
		i_food_x = food0.position.x;
		i_food_y = food0.position.y;
/*
		app.loader.add('musical', 'happy_03.mp3').load(function() {
		    body.on('pointerdown', function() {
		        sound.play('musical', { loop: true });
		        console.log('play');
		    });
		    body.on('pointerdown', function() {
		        sound.stop('musical');
		    });
		});
		body.on('pointerdown', function() {
		        sound.play('musical', { loop: true });
		        console.log('play');
		    });*/
		// Add the sprites data when creating sounds

		/*const sound = PIXI.sound.add('music', 'happy_03.mp3');
		music.sound.play();*/

		PIXI.Loader.shared.add('bgm', 'assets/sounds/bg_music.mp3');
		PIXI.Loader.shared.add('happy', 'assets/sounds/happy_03.ogg');
		PIXI.Loader.shared.add('yumm', 'assets/sounds/yumm.ogg');
		PIXI.Loader.shared.add('eating', 'assets/sounds/eating.ogg');

		PIXI.Loader.shared.load(() => {

			balloon0.position.set(0, 0);
			balloon0.width = W;
			balloon0.height = H;
			stage.addChild(balloon0);

			const bgm = PIXI.loader.resources.bgm;
			bgm.sound.play();
		    const happy = PIXI.loader.resources.happy;
		    body.on('pointerdown', function() {
		    	if(!(mood=="fhappy")) jump();
		        happy.sound.play();
		    });
		    
		    const yumm = PIXI.loader.resources.yumm;
		    food0.on('pointerdown', function() {		    	
		        yumm.sound.play();
		    });

		    const eating = PIXI.loader.resources.eating;

		    var food_levitate = 0;
			var i_mood = mood;
			var move;
			var eyes_follow;
			food0.on('pointerdown', function(event){
				i_mood = mood;
				if(amigo_health<=5){
					mood='hungry';
					//statics
					body.texture = char_body;
					
					eyes_follow = setInterval(function() {
						if(event.data.global.x<body.position.x){
							eyes.texture = char_eyes_l;
							mouth.texture = char_mouth1;
						}else if(event.data.global.x>body.position.x+body.width){
							eyes.texture = char_eyes_r;
							mouth.texture = char_mouth1;
						}else{
							eyes.texture = char_halfopeneyes;
							mouth.texture = char_mouth;
						}
					}, 100);
						
				}
				food_levitate = 1;
				move = setInterval(function() {
					//if(event.data.global.x>food0.width/3 && event.data.global.x<W-food0.width/3){
						if(food_levitate) food0.position.set(event.data.global.x - food0.width/2, event.data.global.y - food0.height/2);
					//}else{
						//if(food_levitate) food0.position.y = event.data.global.y - food0.height/2;
					//}
				}, 10);
			});
			food0.on('pointerup', function() {
				food_levitate = 0;
				clearInterval(move);
				clearInterval(eyes_follow);
				if((food0.position.x>body.position.x-food0.width/2 && food0.position.x<body.position.x+body.width/2) && (food0.position.y>body.position.y-food0.height/2 && food0.position.y<body.position.y+body.height/2)){
						//eaten
						if(mood_v<2) balloon0.texture = t_balloon1; else balloon0.visible=false;
						if(mood_v<5){
							hbar.texture = arr_health[mood_v+1];
							mood_v++;
							eating.sound.play();
							food0.position.set(i_food_x, i_food_y);
						}else{
							food0.visible=false;	
						}
						mood=arr_mood[mood_v];
					}else{
					//return food
					mood = i_mood;
					console.log(mood);
					food0.position.set(i_food_x, i_food_y);
				}
			});



		});

		/*Actions*/

		//jump
		function jump(h=1){
			a=h*5;
			v=15;
			d=1;
			var animJump = setInterval(function(){
				a-=d*0.5;
				for (var i = amigo.length - 1; i >= 0; i--) {
					amigo[i].position.y-=a*v*d;
				}
				//animate shadow
				sdw_factor = ((Math.abs(d*a)/4)+0.75);
				shadow.scale.set(sdw_factor);
				shadow.position.set(xOff - shadow.width/2, (1.2*yOff)+(0.33*W/2));

				if(amigo[0].position.y<0.2*H){
					a=1;
					d=-1;
				}else if(amigo[0].position.y>=1.2*yOff){
					for (var i = amigo.length - 1; i >= 0; i--) {
						amigo[i].position.y=1.2*yOff;
						clearInterval(animJump);
					}
				}
			}, 30);
		}

		//change room
		curr_room = 1;
		arr_rt.on("pointerdown", function changeRoom(){
			if(curr_room < arrt_rooms.length){
				curr_room++;
				room.texture=arrt_rooms[curr_room-1];
			}
			if(curr_room==4)arr_rt.visible=false;else arr_rt.visible=true;
			if(curr_room==1)arr_lt.visible=false;else arr_lt.visible=true;
		});

		arr_lt.on("pointerdown", function changeRoom(){
			if(curr_room > 0){
				curr_room--;
				room.texture=arrt_rooms[curr_room-1];
			}
			if(curr_room==1)arr_lt.visible=false;else arr_lt.visible=true;
			if(curr_room==4)arr_rt.visible=false;else arr_rt.visible=true;
		});

		//animate Mood
		var t = 0;
		var animMood = setInterval(function(){
			if(mood=='smile'){
				//eyes animation
				if(t>=20 && t<25){
					//close
					eyes.texture = char_blink2;
				}else if (t>=25){
					//open
					eyes.texture = char_blink0;
					//reset
					t=0;
				}
				//statics
				mouth.texture = char_smile;
				body.texture = char_body;
			}
			else if(mood=='laugh'){
				//eyes animation
				if(t>=20 && t<25){
					//slit eyes
					eyes.texture = char_blink1;
				}else if (t>=25){
					//close
					eyes.texture = char_blink2;
					//reset
					t=0;
				}
				//mouth animation
				if(!(t%10)){
					mouth.texture = char_mouth;
				}else{
					mouth.texture = char_mouth1;
				}
				//statics
				body.texture = char_body;
			}
			else if(mood=='cutesmile'){
				if(!(t%10)){
					mouth.texture = char_smile1;
					eyes.texture = char_closedeyes1;
				}else{
					mouth.texture = char_smile;
					eyes.texture = char_closedeyes;
				}
				t=t>200?0:t; //reset

				//statics
				body.texture = char_blush;
			}
			else if(mood=='sad'){
				if(t==20){
					eyes.texture = char_eyes_r;
				}else if(t==40){
					eyes.texture = char_eyes;
				}else if(t==60){
					eyes.texture = char_eyes_l;
				}else if (t==80){
					eyes.texture = char_eyes;
					//reset
					t=0;
				}else if(t>80) t=0;
				//static
				mouth.texture = char_sad;
				body.texture = char_body;
			}
			else if(mood=='fsad'){
				if(t==10){
					eyes.texture = char_tearyeyes;
					mouth.texture = char_wavymouth;
				}else if(t==20){
					eyes.texture = char_tearyeyes1;
					mouth.texture = char_wavymouth1;
					//reset
					t=0;
				}else if(t>20) t=0;
				//static
				mouth.texture = char_wavymouth;
				body.texture = char_body;
			}else if(mood=='hungry'){

			}else if(mood=='fhappy'){
				if(t==15){
					jump();
					eyes.texture = char_eyes;
					mouth.texture = char_mouth;
					t=0;
				}else if(t==10){
					eyes.texture = char_closedeyes;
					mouth.texture = char_mouth1;
				}else if(t>15) t=0;
			}

			//inc
			t+=5;
		}, 400);

		/*MOODS*/

		//cute smile
		function fhappy(){
			//eyes.texture = char_closedeyes; mouth.texture = char_smile; body.texture = char_blush;
			mood='fhappy';
			mood_v = 5;
		}
		//smile
		function smile(){
			//eyes.texture = char_eyes; mouth.texture = char_smile; body.texture = char_body;
			mood='smile';
			mood_v = 2;
		}
		//cute smile
		function cutesmile(){
			//eyes.texture = char_closedeyes; mouth.texture = char_smile; body.texture = char_blush;
			mood='cutesmile';
			mood_v = 3;
		}
		//laugh
		function laugh(){
			//eyes.texture = char_eyes; mouth.texture = char_mouth; body.texture = char_body;
			mood='laugh';
			mood_v = 4;
		}
		//sad
		function sad(){
			//eyes.texture = char_eyes; mouth.texture = char_sad; body.texture = char_body;
			mood='sad';
			mood_v = 1;
		}
		//fsad
		function fsad(){
			//eyes.texture = char_tearyeyes; mouth.texture = char_wavymouth; body.texture = char_body;
			mood='fsad';
			mood_v = 0;
		}
		//angry
		function angry(){
			//eyes.texture = char_halfopeneyes; mouth.texture = char_sad; body.texture = char_body;
			mood='angry';
		}

		//render
		function render(){
 			requestAnimationFrame(render);
  			renderer.render(stage);
		}
		render();
		document.body.appendChild(renderer.view);

		function resize() {
			document.getElementsByTagName('canvas')[0].width=W-20;
			document.getElementsByTagName('canvas')[0].height=H-20;
		}resize();
		

	</script>
</body>
</html>