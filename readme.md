
## unocss-present-px-to-rpx

插件需要依赖 presetRemToPx 把 rem 转为 px, 然后把 px 转为 upx
```ts

// uno.config.ts
import { defineConfig } from 'unocss'
import presetRemToPx from '@unocss/preset-rem-to-px'
import presetPxToRpx from 'unocss-present-px-to-rpx'

export default defineConfig({
  presets: [
    presetRemToPx(),
    presetPxToRpx(),
  ],
})
```