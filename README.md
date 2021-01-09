# AlcatelNetworkStatus
For perfectly aligning your Alcatel modem to get the best connection.

# How to set this up
1. Install `node.js`
2. Run `git clone https://github.com/AlgirdasButkus/AlcatelNetworkStatus`
3. Run `cd AlcatelNetworkStatus`
4. Run `node .`
5. You should see your network status.

# How it works
```
POST http://192.168.1.1/jrd/webapi?api=GetNetworkInfo
{"jsonrpc":"2.0","method":"GetNetworkInfo","params":null,"id":"4.1"}
```

# Works on my machine
Works on Linux. May not work on Windows or Mac. I am not going to test and support those.
If you want to change something, feel free to make a pull request.
