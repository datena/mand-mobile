---
title: 更新日志
toc: hidden
---

### 2.0.0

`2019-01-30`      

- Feature
  - `DetailItem`属性`content`增加支持类型[#285](https://github.com/didi/mand-mobile/issues/285)
  - `Dialog`属性`preventScroll`默认值改为`true`[#286](https://github.com/didi/mand-mobile/issues/286)
  - `Radio`属性`value`增加支持类型[#289](https://github.com/didi/mand-mobile/issues/289)
  - `Icon`的字体图标类型增加无前缀类名[#295](https://github.com/didi/mand-mobile/issues/295)
  - `Check`，`CheckBox`属性`name`，`value`增加支持类型[#297](https://github.com/didi/mand-mobile/issues/297)
  - `InputItem`增加属性`virtual-keyboard-vm`，用于支持外部自定义金融键盘
  - `Cashier`增加插槽`footer`，`channels`增加属性`img`

- Fix
  - 去除`InputItem`内对原生输入框光标位置设置 [#268](https://github.com/didi/mand-mobile/issues/268)
  - 补充`index.d.ts`
  - 修复部分组件样式问题

### 2.0.0-rc.5

`2019-01-04`      

- Feature
  - 全量引入时的注册全局组件名增加`PascalCase`[#261](https://github.com/didi/mand-mobile/issues/261)
  - `ScrollView`增加属性`manual-init`和方法`init`
  - `TabBar`, `Tabs`增加属性`immediate`
  - `Swiper`增加属性`transition-duration`

- Fix
  - 修复部分组件样式问题

### 2.0.0-rc.4

`2018-12-21`      

- Feature
  - 优化`NumberKeyboard`输入体验
  - `Cashier`增加插槽`scene`
  - `Picker`增加`default-value`[#255](https://github.com/didi/mand-mobile/issues/255)

- Fix
  - 修复`Popup`连续展示隐藏时失效问题
  - 修复`Steps`样式兼容问题
  - 修复`InputItem`样式问题，增大关闭按钮点击区域
  - `Captcha`的`setError`中不再清除已输入内容

### 2.0.0-rc.3

`2018-12-14`      

🎉🎉🎉 👏👏👏 更多内容查看 <a href="#/zh-CN/docs/migration">从1.x迁移</a>。

### 1.x 

去[GitHub](https://github.com/didi/mand-mobile/blob/1.x/CHANGELOG.md)查看`1.x`的 Change Log。