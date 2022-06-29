## Return Negative

function makeNegative(num) {
  if (num > 0) {
    return num * -1
  }
  else{
   return num 
  }
}

## Sum of Positive

function positiveSum(arr) {
  let arrPositiveSum = 0
  for (let i = 0; i < arr.length; i++){
    if (arr[i] > 0) {
    arrPositiveSum = arrPositiveSum + arr[i]
    }
  }
  return arrPositiveSum
}

## Function 2

function square (num) {
  return num * num
}

## Sum Arrays

function sum (numbers) {
  let numbersSum = 0
  for (let i = 0; i < numbers.length; i++) {
    if (typeof i == 'number') {
      numbersSum = numbersSum + numbers[i]
    }
  }
  return numbersSum
};

## Reversed Strings

function solution(str){
  let strArr = str.split('')
  let revStrArr = []
  let revStr = ''
  revStrArr = strArr.reverse()
  revStr = revStrArr.join('')
  return revStr
}
