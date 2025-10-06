# sort.js
function sorting(arrayToSortayToSort) {
    for(let j = 0; j < arrayToSortayToSort.length - 1; j++) {
        for (let i = j + 1; i < arrayToSortayToSort.length; i++) {
            if (arrayToSortayToSort[j] <=arrayToSortayToSort[i]){
                let temp = arrayToSortayToSort[j]
                arrayToSortayToSort[j] = arrayToSortayToSort[i]
                arrayToSortayToSort[i] = temp
            }
        }
    }
    return arrayToSortayToSort;
}
const sortedarrayToSort = sorting([2,5,2,1,-9])
console.log({ sortedarrayToSort });
