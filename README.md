# install-postcss
Install Postcss in tailwindcss project. Follow the description below.

![Logo](https://lh3.googleusercontent.com/drive-viewer/AFDK6gP7N8Z6X1neI-nf690m7ajKBahE5HBK6J4YMgwkLfD-XHIMfuznvyH_ZqKIp3ES-LHyetJA0GqzlxDhmtm_fwLPUQjA2w=w1366-h657)

#### **1.** Install Postcss in Tailwindcss project.
Open the Terminal from within `your project` and copy and paste the code below in the terminal. ↓↓↓
```bash
npm i postcss postcss-cli autoprefixer
npx tailwindcss init -p
```
</br>

#### **2.** Start the Postcss CLI build process.
Then go to the file called `package.json` in your project and then copy and paste the below code inside the section called `scripts`. ↓↓↓
```bash
"postcss": "npx postcss ./src/css/input.css -o ./dist/output.css --watch"
```
</br>

#### **3.** Run Projects.
Finally, type `npm run postcss` from your project's terminal and then open the `index.html` file in the browser. ↓↓↓
```bash
npm run postcss
```
</br>

𝔸𝕝𝕝 𝕕𝕠𝕟𝕖! 𝕋𝕙𝕒𝕟𝕜𝕤 𝕪𝕠𝕦..
