function migratoryBirds(n, ar) {
    let count = 0
    let str = ar.join('')
    let re;
    [1,2,3,4,5].map(num => {
        let len = str.replace(new RegExp(`[^${num}]`,'g'),'').length
        if (new RegExp(`${num}`).test(str) && len > count) {
            count = len
            re = num
        }
    })
    return re
}
