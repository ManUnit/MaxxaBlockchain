# Maxxa Public Blockchain ( For demo )

Block Explorer : http://maxxa.069thailand.com 

Specification :

Block time : around 9 second faster than original Ehereum as using 14 second.

Mining reware : 0 / block + Transaction fee reward by user pay the gas


Ethereum fork by : Anan P.

# download and run complied below for each OS system it was build-in genesis in files no need to init genesis again 

file : maxxad-linux-armv7	for Rasberri PI III Arm version 7

file : maxxad-linux64      for Linux

file : maxxad-windows-amd64.exe  for Windows 64bit


# running blockchain Example : 

Windows : 

```
c:\> maxxad-windows-amd64.exe  --rpc --rpcport 9971 --rpcapi admin,personal,net,web3,eth --datadir MAXXA

Connect console run new cmd.exe as below command :   

c:\> maxxad-windows-amd64.exe attach  IPC:MAXXA/geth.ipc  

or 

c:\> maxxad-windows-amd64.exe attach RPC:http://127.0.0.1:9971

```
# Contracts was deployed 

Contract for FAIT  DMC: 0x03e75c146937b5ac465c50175a4e934cadd3b0bc

Contract for FAIT MINR : 0xc5089fa9e9706a540fb65f9973eca0c4562d3501

Contract for FAIT MUSD : 0x6d997eb4b3aa899c3ca0c287ace08b9a0566d8c5  

# Blockchain genesis code donwload compiled files in this respository were build-in genesis you can run without genesis again 
```


{
        "config":{
        "chainId":2345890,
        "homesteadBlock":0,
        "eip150Block":0,
        "eip155Block":0,
        "eip158Block":0,
        "byzantiumBlock":100
       },

        "coinbase":"0xc3992c21147be20f1661c484e0efd88527b54af6",
        "difficulty":"10000",
        "extraData":"0x687474703a2f2f7777772e6176657374612e696f0a496e6e6f7661726f2047726f757020436f2e2c4c74642e0a42616e676b6f6b0a546861696c616e64",
        "gasLimit":"0x7A1200",
        "nonce":"0x00000000000001",
        "mixhash":"0x0000000000000000000000000000000000000000000000000000000000000000",
        "parentHash":"0x0000000000000000000000000000000000000000000000000000000000000000",
        "timestamp":"0x5C29A41F",
        "alloc":{
                "0xda74239552b5f1c388cb45cc0bac70fe707bb61e":{"balance":"0"}
                ,"0xadccf315ca305deed743faf0f31729c1715709d1":{"balance":"100000000000000000000000000"}
                ,"0xffa7fa59314ecd443f28b8bb9c02eee4678abeb7":{"balance":"95000000000000000000000000"}
                ,"0x24a23bf0370c57ec140e57763cc95160e9e9c9ca":{"balance":"5000000000000000000000000"}
                ,"0x4205b4ba8aea29cc4ab053e17eb9a162cb64c45c":{"balance":"78900000000000000000000000"}
                ,"0xce1243e932da83072f3d446e64ef1c21edec9c60":{"balance":"20000000000000000000000000"}
                ,"0xc82a7bc4f0c70b10cbaaa6850135f9b0cda05081":{"balance":"0"}
        }

}
```
