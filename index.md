### Venkata's User Page
Hi, my name is venkata and I am a third year ***CS*** major here at UCSD.


## interests 
Watching movies
Playing basketball 
Listening to music

## Favorite Quote 
> "Freedom is not worth having if it doesn't include the freedom to make mistakes." 


## Some Code from Uncompress function of a Huffman encoding program. 

`
#include "HCTree.hpp"
#include <cmath>
int main(int argc, char* argv[]) {
    FancyInputStream files( argv[1]);
    vector<int> freq; 
    
    if(!files.good()){
        error("The file is invalid");
    }

    if(files.filesize() == 0){
       FancyOutputStream ash(argv[2]);
        return 0;
    }

    int count = 0; 

    vector<int> num;
`


