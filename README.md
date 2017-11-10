## Introduce  

this is a simple script use useragent to judge browser

## Quick to start:

install:     
`npm install --save yu-judge-browser `    
import:  
`import browser from 'yu-judge-browser' `

## Example

>You can use `npm run dev` to check the example file in node package

    console.log(browser)
    
    {
        "versions":{
            "trident":false,
            "presto":false,
            "webKit":true,
            "gecko":false,
            "mobile":false,
            "ios":false,
            "android":false,
            "iPhone":true,
            "iPad":false,
            "qq":false,
            "wechat":false,
            "webApp":false
        },
        "language":"zh-cn"
    }"
        
## JSDoc

 * @returns {object[]} versions - true or false of different terminals
 * @returns {boolean} [versions[].trident] - is ie ?
 * @returns {boolean} [versions[].presto] - is opera ?
 * @returns {boolean} [versions[].AppleWebKit] - is apple,chrome ?
 * @returns {boolean} [versions[].gecko] - is firefox ?
 * @returns {boolean} [versions[].mobile] - is mobile ?
 * @returns {boolean} [versions[].ios] - is ios ?
 * @returns {boolean} [versions[].android] - is android ?
 * @returns {boolean} [versions[].iPhone] - is iPhone ?
 * @returns {boolean} [versions[].iPad] - is iPad ?
 * @returns {boolean} [versions[].qq] - is qq browser ?
 * @returns {boolean} [versions[].wechat] - is wechat browser ?
 * @returns {boolean} [versions[].webApp] - is webApp ?
 * @returns {string} language - language of this web

## Links

##### github  
see https://github.com/watanabeyu0709/yu-judge-browser
##### npm  
see https://www.npmjs.com/package/yu-judge-browser
