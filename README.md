# CodeSnippets   
Xcode Common Code Snippets.   
Path:`~/Library/Developer/Xcode/UserData/CodeSnippets`      
1.check out the project using: `git clone https://github.com/Gnakeg/CodeSnippets.git`   
2.`cd CodeSnippets/`   
3.`cp *.codesnippet ~/Library/Developer/Xcode/UserData/CodeSnippets`   
4.restart Xcode  

#  Snippets List  
- `gkweakself`:__weak __typeof(self) weakSelf = self;  
- `gkstrongself`:__strong __typeof(weakSelf) strongSelf = weakSelf;
- `gkinit`:init code   
- ```self = [super init];
   if (self) {
        
   }
   return self;
- `gkhidekeyboard`:hide keyboard when touch background
- `gksigleton`:Class method that returns a singleton instance
- `gkproxxx`:@property(xxx)
- `gkuitableview`:UITableViewDelegate and UITableViewDataSource of UITableView
