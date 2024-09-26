# gomobile-test

### 1.go install golang.org/x/mobile/cmd/gomobile@latest

### 2.export PATH=$PATH:~/go/bin

### 3.gomobile init
### 4.go get golang.org/x/mobile/cmd/gomobile
### 5. gomobile bind -v -o ./Greeter.xcframework -target=ios,macos

### 6.Drag-and-drop Hello.xcframework from the desktop to the project navigation window.
 ###  This will automatically include the Greeter.xcframework into the project.

## swift code
 ### 1.import Greeter
 ### 2.let receiveInfo = Greeter.GreeterGreetings("jojo")  print(receiveInfo)
