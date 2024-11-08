# Nikolai Kanurin

## Contact information

- **email:** delaveur@yandex.ru
- **phone:** +7(985)065-37-73
- **telegram:** @Delaveur

## Brief Self-Introduction

I am a content-manager in Vobus group. I have started my career in 2011 with zero skills in html/css or programming. Since then i have learned a lot, especially how to work in different CMS, CRM, and web-servers and how to work with integrations to the web site. 

But since then i haven't get any essential skills in programming. I hope that studying at RS School will provide me with a strong foundation to start my journey as a programmer. And i will do everything that depends on me.

## Skills

- CSS, HTML
- CMS (Mostly 1C-Bitrix)
- CRM
- Adobe Photoshop
- Basic server setup

## Code Example

**Categorize new member 7kyu task from Codewars** - The Western Suburbs Croquet Club has two categories of membership, Senior and Open. They would like your help with an application form that will tell prospective members which category they will be placed.

To be a senior, a member must be at least 55 years old and have a handicap greater than 7. In this croquet club, handicaps range from -2 to +26; the better the player the lower the handicap.

**Solution code**

```
function openOrSenior(data){   
    var result = [];  
        for (var i = 0;i < data.length; i++) {  
            if (data[i][0]>=55 && data[i][1]>7) {  
                result[i]="Senior";  
            } else {  
                result[i]="Open";  
            }  
        }  
    return result;  
}  
```

