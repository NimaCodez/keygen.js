# keygn

#### :fire: The Ultimate CommandLine Tool for creating different type of keys instantly, to make your development faster.

🧐 Have you ever wanted to generate a secret key for your access tokens and resfresh tokens and etc?
✅ Well it would be a yes definetely.

# Practices
At First glance you'd say: "Ok, I will find a hard and meaning-less sentence and hash it using MD5 (horrible) or SHA family and use it as a secret (or salt). <b>*but this is actually a bad security practice.*</b> ❌
Cause as you know all those senteces and words could be converted back to them readable way.

### ☹️ What should we do then?
Aha! here you are.
<b> Use `keygn` right into your cmd and generate a safe key for any kind of encoding and decoding things you want to do!

## 🚀 Installation
```sh
npm i -g keygn
```

## 🪄 Usage
```sh
keygn
```

1. Answer the first question about the length. (e.g `64` would generate a 64 byte key).
![image](https://github.com/NimaCodez/keygn/assets/85389307/f79a7e60-cdfa-45f6-8377-0f2b8a58e521)

2. Then Choose how your key should be given to you. </br>
![image](https://github.com/NimaCodez/keygn/assets/85389307/c6843af7-5cf2-4a77-9ca7-05f8953c7190)

3. 👽 And Done!
![image](https://github.com/NimaCodez/keygn/assets/85389307/8e80d51e-6e1f-485b-a6dd-87f44480fe12)

<b><em>Tip: both questions have default values (64 for length adn Hexadecimal (hex) for key tyoe. So you can just press [Enter] and Chill 🦭

Sample Output:
```sh
YOUR KEY: 3ba15c658a6c9c659908cb6893d9761a26e0641af33a0cb396a13d9e7b928c626882d3b050575b027da0717c48c745d633a5dfe7d4523aeea89648b508d864f9
```
