public static int indexOf(String a, String b){
    
    if(a.length()<b.length())return -1;
    else if (a.substring(0,b.length()).equals(b)){
        return 0;
    }
    int tally = indexOf(a.substring(1),b);
    if (tally==-1){
        return -1;
    }
    else{
        return tally+1;
    }
}
