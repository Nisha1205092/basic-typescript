### Introduction to TypeScript: 

##### install typescript globally: 
- in my case, I had to use the following: 
- ```npm uninstall -g typescript --force```
- ```npm install -g typescript --force```
- after that, running ```tsc``` works fine
- running ```tsc --init``` will generate a tsconfig.json file

#### Inside tsconfig.json
- most common configurations
    - "target": "ES2016" ---> better for supporting most browsers
    - "strict": true ---> force everything to have a specific type
    - "module": "CommonJS"  ---> older commonJS syntax will be generated