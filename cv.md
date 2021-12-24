
## GULZHAN 
  

#### Contacts:

- Discord: Gulzhan#5889

**Hard Skills:** 

- HTML/CSS/Javascript/React/Git - junior level
- English - near fluent (TOEFL iBT score: 116 out of 120)
- Trained in Agile/Scrum (certificate)

**Code Example:**

```
        const scrollUp = document.querySelector('.scrollUp')
        window.addEventListener('scroll', function ( event ) {
            let isScrolling;
            if (document.body.scrollTop > 1200 || document.documentElement.scrollTop > 1200) {
                scrollUp.style.display = "block";

                window.clearTimeout( isScrolling );

                isScrolling = setTimeout(function() {
                if(scrollUp.style.display === "block"){
                scrollUp.style.display = "none";}
	            }, 5000)

            } else {
                scrollUp.style.display = "none";}
            })
```