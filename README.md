let item_1 = 5
console.log (item_1)

let item_2 = 3
console.log(item_2)

let item_3 = (item_1 + item_2)
console.log(item_3)

let item_4 = "Yolochka"
console.log(item_4)

console.log(item_3 + item_4)

console.log(item_3 * item_4)

let item_5 = item_3
console.log(item_5)

let item_6 = 15 

let item_6_type = item_6
console.log(item_6_type)

console.log('item_6==', item_6, 'item_6_type==', typeof item_6)

let item_7 = String(item_6)
console.log(item_7)

let item_7_type = item_7
console.log(item_7_type)

console.log('item_7==', item_7, 'item_7_type==', typeof item_7)

let age_1 = 10;
let age_2 = 18;
let age_3 = 60;

if (age_1 < age_2){

    console.log('You don`t have access cause your age is ' + age_1 + ' It`s less than ' + age_2)

}

else if (age_1 >= age_2 && age_1 < age_3){
    console.log('Welcome!')

}

else if(age_1> age_3){
    console.log('Keep calm and watch Culture channel')
}

 else {
     console.log("Ttechical work")
 }






OUTPUT
evgenii@MacBook-Air javascript % node "/Users/evgenii/Downloads/javascript/JS. HW_1.js"
5
3
8
Yolochka
8Yolochka
NaN
8
15
item_6== 15 item_6_type== number
15
15
item_7== 15 item_7_type== string
You don`t have access cause your age is 10 It`s less than 18
evgenii@MacBook-Air javascript % 