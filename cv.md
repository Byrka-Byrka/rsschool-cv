## Kravtsov Aleksandr
### Contacts :
- **Location** : Mogilev, Belarus
- **Email** : <7250603@gmail.com>
- **Phone** : +375(33)309-74-94
---
### About me :
I graduated from Mogilev State A. Kuleshov University.  
**Specialization**: Sports and Tourism Management.  
**Qualification**: Teacher.  
I am styding informational tecnologies for 1 year. I think that i self disciplined, sociable, open minded person.
I realize that future is technology and development, that's why i chose IT sphere.

---
### My skills :
- HTML
- CSS
- BEM
- JavaScript
- DOM
- React
- React Redux
- Git
---
### Code Example :
```sh
    function arrPropSort(arr){
        let personsProps = arr.reduce((accum,current) =>{
            let numOfKeys = Object.keys(current).length;
            if ( numOfKeys < 8 ) return accum;
            if ( numOfKeys >= 8 ) return [...accum, current]
        },[])
        personsProps.sort((a,b) => (Object.keys(a).length - Object.keys(b).length))
        personsProps.reverse();
        return personsProps;
    }
```
```sh
function explode(s) {
  let arr = s.split('')
  let result = ''
  arr.forEach(item =>{
    for(let i = +item; i>0; i--){
      result += item
    }
  })
  return result;
}
```
---
### Education 
- udemy :
    - [WEB-developer 2021](https://www.udemy.com/course/webdeveloper/)
    - [The Complete JavaScript Course](https://www.udemy.com/course/javascript_full/)
-  IT STEP Academy : [FRONT-END](https://front-end.itstep.by/) course

---
### English level : **A2** 