# binary
int bsearch (const vector<int> &A ) {
    int inicio = 0, final = n;
    while ( final−inicio >1) {
        int mid = ( inicio+final ) /2;
        if ( A[mid] <= A[mid+1] ) {
            inicio = mid;
        } else {
            final = mid;
        }
    }
    return final ;
}
