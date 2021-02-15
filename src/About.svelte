<article id="about">
   <section id="me">
      <img src="/images/profile" alt="Espen Berget profile" />
      <p>
         I'm a mostly self-taugh web developer from Oslo, Norway with a broad interests in programming. Web development fits me because it contains a wide array of
         capabilities. I'm interested in music, so WebAudio intrigues me. I like to make some games, so canvas, CSS Animations & WebGL/WebGPU appeals. 
         I've think exploring data is fun and so D3.js is engaging. The prosess of programming and seeing the product take shape before your eyes is incredibly rewarding. Lastly, witnessing the lessons you learn about
         HTML, CSS, and JS in the last project being used and improved in the next is thrilling!
      </p>
   </section>
   <section id="questions">
      <div class="question">
         <h1>Why web development?</h1>
         <p>The web offers a uniq mix of reach and flexibility. You could make your own DAW using WebAudio, then move on to game development using WebGL,
            and perhaps put you design skills to the test and make a nice landing page for the products you made. All of these could run on any modern
            device, given that you followed good practises. This is to tempting to say no to. Also if you get sick og JavaScript, there are a bunch of
            compile to JS languages out there, aswell as WebAssembly. It seems that everyone wants a pice of the web, better learn it!  
         </p>
      </div>
      <div class="question">
         <h1>How long have you been a developer?</h1>
         <p>I been programming for 7+ years now, but never found my place. The first things I made was websites in pure HTML/CSS. So going back to 
            web development is full circle for me. In those 7 years I've tried everything, or so it feels. From functional with Haskell to logical with Prolog,
            aswell as Elixir, Clojure, Go, Java, etc... These days I'm happy with regular JavaScript. 
         </p>
      </div>
      <div class="question">
         <h1>What can we expect from you?</h1>
         <p>I enjoy solving problems, and I am not one to say that something is to difficult, only that it may require time. I often know what I can do,
            and what I must learn. I like to follow the mantra of try, read, ask. I enjoy the old school hacker way of attacking a problem head on, but do
            recognise it's limitations. It did not take long for me to deside that Svelte would be needed in making this site.
         </p>
      </div>
      <div class="question">
         <h1>What are your aspirations?</h1>
         <p>I want to become proficient in many web technologies, and also know some backend. While I enjoy a well design webpage, It's not my main focus. 
            In some year time I see myself being skilled the use of web APIs and capable of makeing a lot of varied products,
            as well as publishing and maintaining them.
         </p> 
      </div>
   </section>
   <section id="info">
      <div>
         <h1>Languages</h1>
         <ul>
            <li>JavaScript</li>
            <li>TypeScript</li>
            <li>PureScript</li>
            <li>Elm</li>
            <li>Go</li>
            <li>Haskell</li>
            <li>R</li>
         </ul>
      </div>
      <div>
         <h1>Frameworks</h1>
         <ul>
            <li>React</li>
            <li>Svelte</li>
            <li>JQuery</li>
            <li>SCSS</li>
         </ul>
      </div>
   </section>
</article>
<style>
   #about {
      padding: 1rem;
      padding-top: 2.5rem;
      height: auto;
      display: flex;
      flex-direction: column;
      background-color: #3d464f;
      color: rgb(222, 233, 237);
      line-height: 1.5;
   } 

   #questions {
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: space-evenly;
   }

   .question {
      width: 50%;
      max-width: 600px;
      margin-bottom: 2rem;
      border-radius: 5px;
      padding: 0.7rem;
      background-color: rgb(206, 205, 205);
      color: rgb(36, 36, 36);
      align-self: center;
      position: relative;
   }

   .question:nth-child(even) {
      right: 200px;
      margin-left: 2rem;
   }
   .question:nth-child(odd) {
      left: 200px;
      margin-right: 2rem;
   }

   #me {
      width: 75%;

      display: flex;
      align-items: center;

      align-self: center;
   }

   #me img {
      margin: 1rem;
      max-width: 250px;
      max-height: 300px;
      border-radius: 5px;
   }

   #info {
      display: flex;
      justify-content: space-evenly;
      border: 3px dotted rgb(206, 205, 205);
      border-radius: 10px;
      max-width: 500px;
      min-width: 400px;
      align-self: center;
   }

   #info h1 {
      text-align: center;
      color: rgb(148, 154, 221);
   }

   #info ul {
     list-style: "- ";
   }

   @media screen and (max-width: 750px) {
      #me {
         flex-direction: column;
      }

      #me img {
         align-self: center;
         border-radius: 50%;
      }

      #questions {
         align-items: center;
      }

      .question {
         width: 75%;
         position: static;
         margin-left: 0 !important;
         margin-right: 0 !important;
      }

      #info {
         flex-direction: column;
         align-items: center;
         border: none;
      }
   }

</style>
