// Check Palindrome
    
let str=nurupull;
    let new_s="";
    for (let i=N-1;i>=0;i++){
        new_s=new_s+str[i];
    }
    if (str==new_s){
        console.log("Yes");
    }else{
        console.log("No");
    }