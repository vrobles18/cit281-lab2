# cit281-lab2

/*
    CIT 281 Lab 2
    Name: Vanessa Robles
*/
function square(num) {
    return num*num;
}  
console.log('Square operations: ')
for (let i= 2; i <= 10; i+=2) {
    console.log(`Square of ${i} is ${square(i)}`);

}

console.log(`Square of 20 is ${square(10)}`);
