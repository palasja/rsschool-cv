# Yakubenka Ivan
![](https://lh3.googleusercontent.com/9WhAajMXef88VGZa7pOFsi6vLJgsgYFIL9S-dubIlFcEZlfmM06ejpgq5MLzOKl1xQhtGxNDOGYkamnLFTVj3IKiFCX_UQGrxb__-PPrAIqkPGSh7pXK_bi2DPzxcoXQuFxaKl6mCw=w2400)
### CONTACTS
- **tel** *+375298337619*
- **email** *palasja@gmail.com*
- **discord** *@palasja*
### ABOUT ME
I am 31 year old. I am working as engineer and I am maintaining PC, servers and peripherals. 

I started learn programming from HTML about 8 years ago and since I learned php, js, css, java, SQL but I used it only for simple learning projects.

I can't use C# or java on my work so I learned bath for automatize some process. In last year I accepted offer for work on real project as front-end developer and after a month I had courses C#.
### SKILS
- JS (NotePad++, Chrome, VS Code, jq)
- CSS (NotePad++, Chrome, VS Code)
- HTML (NotePad++, Chrome, VS Code)
- java (Eclipse)
- C# (Visual Studio)
- SQL (TSQL, MS SQL Server)
- GIT (GitHub)
### CODE EXAMPLE
```
function(nums, target) {
    let res = [0,0];
    let end = false;
    let tmp = 0;
    for(let i=0; i< nums.length; i++){
        tmp = target - nums[i];
        for(let j=i+1; j < nums.length; j++){
            if(nums[j] == tmp){
                res[0] = i;
                res[1] = j;
                end = true;
                break;
            }
         }
    if(end) break;
    }
    return res;
};
```