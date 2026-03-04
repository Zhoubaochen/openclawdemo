安装nodejs：
1、install nvm:curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.4/install.sh | bash
2、\. "$HOME/.nvm/nvm.sh"
3、nvm install 24

安装openclaw：
1、npm i -g openclaw
2、方法2，from source
npm install -g pnpm
git clone https://github.com/openclaw/openclaw.git
cd openclaw

pnpm install
pnpm ui:build # auto-installs UI deps on first run
pnpm build

pnpm openclaw onboard --install-daemon

# Dev loop (auto-reload on TS changes)
pnpm gateway:watch

安装opencode：
1、npm i -g opencode-ai@latest
