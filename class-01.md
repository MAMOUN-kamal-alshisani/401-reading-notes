# class-01-reading-notes


## Describe (in plain English) what Array.map() does:
***it is an array method that iterates over the the content in the array***

## Describe (in plain English) what Array.reduce() does:
***The arr.reduce () method in JavaScript is used to reduce the array to a single value and executes a provided function for each value of the array (from left-to-right) and the return value of the function is stored in an accumulator.***
''www.geeksforgeeks.org/javascript-array-reduce-method/''

## 3. superagent()
const getCharacters=()=>{
  superagent.get('https://swapi.dev/api/people?format=json')
  .then( data => {
    let newData=[];
    let retunedData=data.body.results;
    newData=retunedData.map(el=>{
      let key=el.name;
      let value=el.url;
      return {[key]:value}
    });
    console.log(newData) ;

  })
  .catch(err => console.error(err));
}
getCharacters();

async function test(cityName) {
  let data = await superagent.get(`https://geocode.xyz/${cityName}?json=1`);
  console.log('latitude ',data.body.latt);
  console.log('longitude ',data.body.longt);
}

test('amman');
