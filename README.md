<div align="center">
    <h1>🐱 Catfetch</h1>
    Catfetch is a small and cute fetch program written in Go
    <br>
    <br>
    <img src="https://domiscute.com/6h5W0AA34.png"></img>
</div>

# Installation

Download a prebuilt binary from the releases or actions 

or

DIY

```sh
git clone https://github.com/Domterion/catfetch
cd ./catfetch/
go mod download
cd ./cmd/catfetch/
go build -ldflags "-w -s"
sudo install -m755 ./catfetch /usr/bin/catfetch
cd ../../..
rm -rf ./catfetch/
catfetch
```

# License
MIT
