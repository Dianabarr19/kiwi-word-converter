# kiwi-word-converter

<h2>Description:</h2>
<br>
Word converter is able to transform numbers into a combination of words; using a T9 or Phonewords style. 
For example: ‘23’ user input will have as an output: <strong> ad, ae, af, bd, be, bf, cd, ce, cf.</strong>
<br>
As 0 and 1 does not have any values (letters) if the user inserts these numbers it will just ignore them (return an empty string).
<br>
The backend is coded in NodeJS, using express; and the frontend is coded with ReactJS and Sass.
<br>

<h2> Installation:</h2>
<br>
<ul>
  <li> To use word converter locally, first you have to clone it to your computer.</li> 
  <li> After, you need to open the file and inside the <strong>frontend</strong> folder, type <strong> npm install </strong> in the terminal</li>
  <li> Wait until it is installed, move to <strong>server</strong> folder and once again type: <strong> npm install</strong>. </li>
  <li> Whenever npm is installed in server and frontend folders; in <strong>server folder</strong> type <strong>npm run dev</strong> in the terminal</li>
  <li> And finally, the server should open world converter in local host: <strong>http://localhost:3000</strong></li>
</ul>

<h2> How to use it? </h2>
<br>
All numbers (besides 1 and 0) are clickable. you can use this buttons or you can just simply use your keyboard in the 'transparent' input bar (right above the numbers) and click on the 'Get Combinations' button. 
<br>
As a result word converter will return:
<ul>
  <li> First a combination of letters involving the numbers selected. </li>
  <li> And below this, using an API the app will return a suggestion of words (1 per) per combination of letters </li>
</ul>
<br>
Here is a small video so you have a brief idea of how word converter works 🤓👇
<br>

https://user-images.githubusercontent.com/90432547/169597455-1b45a3ad-2227-482b-91c3-3d3eaa10f613.mov

<h2> Final Thoughts:</h2>
<br>
Doing word converter was definitely a challenge, I had to learn NodeJS to code the backend, and even though I have some knowledge of ReacJS, I had to do a lot of research in order to achive what I was looking for. I worked on this project for over a week and I am happy and satisfied with the final result, and I definitely learned a lot in the process of creating word converter. Still, there are some aspects I would like to polish, but I had to meet a deadline, so hopefully I can work after in these aspects: such as improving the front end, specially the part of how the results/combinations and recommended words look. Also, The code needs some refactoring, and implementing some tests; as I have never done a frontend test, so in a near future (with some luck) when I have more coding knowledge I can polish this app🤩. 
