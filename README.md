# 安装 pnpm，提升依赖的安装速度
npm config set registry https://registry.npmmirror.com
npm install -g pnpm
# 安装依赖
pnpm install

# 如下命令，二选一即可，启动对应的前端模版：
# 启动服务（ant-design-vue）
npm run dev:antd
# 启动服务（element-plus）
npm run dev:ele
