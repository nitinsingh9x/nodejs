# nodejs
chmod 400 aws_1.pem
ssh -i "aws_1.pem" ec2-user@ec2-54-161-25-157.compute-1.amazonaws.com

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
source ~/.bashrc

nvm install --lts
npm install puppeteer


sudo yum install libXcomposite libXdamage libXrandr libgbm libxkbcommon pango alsa-lib atk at-spi2-atk cups-libs libdrm

const browser = await puppeteer.launch({
      headless: true,
    args: [
  '--no-sandbox',            
  '--disable-setuid-sandbox', 
  '--disable-dev-shm-usage', 
  '--disable-accelerated-2d-canvas',
  '--no-first-run',
  '--no-zygote'
  '--disable-gpu',
  '--disable-software-rasterizer',
  '--disable-web-security', 
  '--disable-popup-blocking', 
  '--ignore-certificate-errors',
  '--allow-insecure-localhost',
],
});
