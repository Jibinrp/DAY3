# DAY3
JSON iterate forloop

for:
for (let i = 0; i < 9; i++) {
  str = str + i;
}

for..of:
var mycars = [{name:'honda'}, {name:'maruti'}];

for (var car of mycars) 
{
  document.write(car.name + "<br />");
}

for..in:
for (const key in res){
  if(obj.hasOwnProperty(key)){
    console.log(`${key} : ${res[key]}`)
  }
  
  forEach:
  repos.forEach((repo) => {
  Object.entries(repo).forEach(([key, value]) => {
    console.log(`${key}: ${value}`);
  });
.
