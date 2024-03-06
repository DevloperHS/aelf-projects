# aelf-projects
All projects related to aelf blockchain are stored here.


# Run Project 
1. Check Node Installation
`node --version`
2. Check Dotnet Install - `dotnet --version`
3. (Optional)Install Dotnet - `sudo apt-get update &&   sudo apt-get install -y dotnet-sdk-8.0`

Important:  Ensure **obj** and **bin** folders on both *src* and *test* directory have been deleted! 
Also, you are required to delete the hello_world.proto file from the test/Protobuf/stub directory.

4. Navigate to test folder and run
   ```
   dotnet test
   ```
