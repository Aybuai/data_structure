# data_structure

.
├── example              runtime-core 测试文件
├── lib                  roll up 打包runtime 的库
├── src                  源码
│   ├── reactivity       reactivity 响应式
│   │   ├── src          reactivity 实现文件
│   │   └── tests        reactivity 测试文件
│   ├── runtime-core     runtime 通用逻辑
│   ├── runtime-dom      runtime custom render个性化
│   ├── shared           通用抽离方法
│   └── index.ts         mini-vue 出口
│  
├── README.md
├── package.json
├── babel.config.js      解决jest esm和ts支持
├── rollup.config.js     rollup配置文件
└── tsconfig.json        ts配置文件
