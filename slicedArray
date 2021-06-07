let incomingArray = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30];

function slicedArray(array, numberOfElement){
    len = array.length;
    numberOfArrays = Math.ceil(len/numberOfElement);
    const res = [];
    for(let i = 0; i < len; i += numberOfElement){
        const chunk = array.slice(i, i + numberOfElement);
        res.push(chunk);
    }
    return res; 
}

console.log(slicedArray(incomingArray, 10));
