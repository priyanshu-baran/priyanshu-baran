    Document
        body {
            padding: 0;
            margin: 0;
            background-color: #0d1116;
        }

        #particles-js {
            width: 800px;
            height: 387px;
            background-color: #0d1116;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            border: 1px solid purple;
            opacity: 0.9;
        }

        #typewriter {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -60px);
            font-size: 3rem;
            line-height: 3rem;
            color: #fff;
            text-align: center;
            font-family: 'Roboto', sans-serif;
            font-weight: 500;
            clip: auto;
            z-index: 1;
            background: -webkit-linear-gradient(#5115b9, #e010e3);
            background-clip: text;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        #typewriter2 {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, 20px);
            font-size: 2rem;
            line-height: 3rem;
            color: #fff;
            text-align: center;
            font-family: 'Roboto', sans-serif;
            font-weight: 500;
            z-index: 1;
            background: -webkit-linear-gradient(#5115b9, #fa00ff);
            background-clip: text;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        particlesJS.load('particles-js', 'GIFCreator/assets/particles.json', function () {
            console.log('callback - particles-js config loaded');
        });

        new Typewriter('#typewriter', {
            delay: 20,
        }).typeString('Hey there, I\'m Priyanshu 👋')
            .pauseFor(3000)
            .deleteAll(10)
            .typeString('I\'m a frontend developer 👨‍💻')
            .pauseFor(3000)
            .deleteAll(10)
            .typeString('I\'m a maker 🏗')
            .pauseFor(3000)
            .deleteAll(10)
            .typeString('Connect me on linkedin 👇')
            .pauseFor(3000)
            .deleteAll(10)
            .typeString('Follow me on twitter 👇')
            .pauseFor(4000)
            .start();

        new Typewriter('#typewriter2', {
            delay: 20,
        }).pauseFor(1000)
            .typeString('Nice to meet you.')
            .pauseFor(2000)
            .deleteAll(10)
            .pauseFor(1000)
            .typeString('Javascript, HTML, React, CSS.')
            .pauseFor(2000)
            .deleteAll(10)
            .pauseFor(1000)
            .typeString('Arduino, ESP8266, ESP32.')
            .pauseFor(2000)
            .deleteAll(10)
            .pauseFor(500)
            .typeString('in/priyanshu-baran')
            .pauseFor(3000)
            .deleteAll(10)
            .pauseFor(500)
            .typeString('@Priyanshu-Baran')
            .pauseFor(4000)
            .start();
