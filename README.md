# 1. Hafta Ödevi

```
// 1
arr1.unshift("a")
console.log(arr1)

// 2
arr1.push(6)
console.log(arr1)

// 3
arr1.pop()
console.log(arr1)

// 4
arr1.shift()
console.log(arr1)

// 5
const newArray = arr1.concat(arr2)
const newArray2 = [...arr1, ...arr2]

console.log(newArray)
console.log(newArray2)

// 6
function searhVal(arr,val) {
    if(arr.includes(val)) {
        return true
    } else {
        return false
    }
}
console.log(searhVal(arr2,"h"))


// 7
console.log(arr2.indexOf('h'))

// 8
arr2.splice(0,4)
console.log(arr2)
let newArr = arr2.slice(3, arr2.length - 1)
console.log(newArr)


// 9
function sumArr(arr) {
    arr.map((item) => {
        if((typeof item) === "string") {
           let index = arr.indexOf(item)
           return arr[index] = 0
        }
    })
    console.log(arr)

    return arr.reduce((a,b) => a + b, 0)

}

console.log(sumArr(arr1))

// 10

function stringfyArr(arr) {
    arr.map(item => {
        let stringItem = item.toString()
        console.log(typeof stringItem)
    })
}
stringfyArr(arr1)


// 11
let findIDVal = arr3.filter(x => x.id === 221)
console.log(findIDVal)

// 12
let aliUsers = arr3.filter(x => x.name === 'ali')
console.log(aliUsers)

// 13
function sumID(arr) {
    let arrID = [];

    for( let i = 0 ; i < arr.length ; i++) {
        arrID.push(arr[i].id)
    }

   return arrID.reduce((a,b) => a + b,0)
}

console.log(sumID(arr3))

```
