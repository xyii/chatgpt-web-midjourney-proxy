# 功能升级日志

#  计划 
# 2.25.2
- 🐞 修复：gpt-image-1 无法同时传多个图片 #634

# 2.25.1
- 😄 新增：支持 suno 模型 `v4.5+` , 将 mv 修改为`chirp-bluejay`
# 2.24.10
- 😄 新增：支持 `reasoning_content`

# 2.24.9
- 😄 新增：mj `图生视频` `图片编辑`

# 2.24.8
- 😄 新增：`flux-kontext-pro` `flux-kontext-max` 模型

# 2.24.7
- 😄 新增：riffusion 音乐模块
- 😄 改进：mj 按钮如果没有预先设置 则直接显示

# 2.24.6
- 😄 新增：mj v6.1 v7的放大   关于MJ V6.1 和 V7 没有放大按钮 #635
- 😄 新增：kling-v2-master 模型
# 2.24.5
- 😄 新增：pix 运镜

# 2.24.4
- 🐞 修复：oref 空 导致 trim错误

# 2.24.3
- 🐞 改进：mj 默认为 v7
- 🐞 改进：mj 支持 oref 全面参考 

# 2.24.2
- 😄 新增： suno `v4.5`  model 为 `chirp-auk`
# 2.24.1
- 😄 新增：gpt-image-1 dall.e-2 支持 v1/image/edit 支持多图
- 🐞 改进：默认上传改为5M

# 2.23.10

- 😄 新增：gpt-image-1 这个是dall-e格式
- 😄 新增：pixverse 的 `v4`版本

# 2.23.9
- 😄 新增：rumwayml 支持 gen4_turbo

# 2.23.8
- 🐞 改进：识图默认放开都支持 只有gpt-3.5 已知不支持
- 🐞 改进：服务端模型 支持搜索

# 2.23.7
- 😄 新增：模型 mj 7.0

# 2.23.6
- 🐞 修复：2.23.4依旧出现ds-R1不展示思考过程的问题 #611
- 😄 新增：模型 从服务端的 /v1/models 拉起


# 2.23.5
- 😄 新增：`grok-3`,`grok-3-reasoner`,`grok-3-deepsearch` 模型
- 😄 新增：`gpt-4.5-preview-2025-02-27`,`gpt-4.5-preview` 模型

# 2.23.4
- 🐞 修复：`deepseek-v3` `deepseek-r1` 识图处理，需要中转支持
- 🐞 修复：`deepseek-r1` think 思考过程显示优化



# 2.23.3
- 😄 新增：`deepseek-v3` `deepseek-r1` 模型

# 2.23.2
- 😄 支持：Pixverse 模版特效
- 😄 支持：kling 支持 model 选型 `v1` `v1.5` `v1.6`

# 2.23.1
- 🐞 修复：Pixverse 时长支持8s 而非10s
- 😄 支持：Pixverse style风格
- 🐞 修复：suno 后端转发目录使用 `/suno`

# 2.22.10
- 😄 支持：视频模型 Pixverse
- 😄 支持：Pixverse 图片、前后帧、扩展

# 2.22.9
- 😄 新增：realtime 可设置模型 `gpt-4o-mini-realtime-preview-2024-12-17` `gpt-4o-realtime-preview-2024-12-17` `gpt-4o-realtime-preview-2024-10-01`
# 2.22.8
- 😄 新增：o1  o1-2024-12-17

# 2.22.7
- 😄 修改：suno upload 二次创作方式

# 2.22.6
- 😄 支持：viggle V3-Beta
- 😄 支持：pika 2.0
- 😄 新增：pika 3个效果

# 2.22.5
- 🐞 修改：suno默认版本为V4


# 2.22.4
- 🐞 修复：mj shorten
- 🐞 修复：mj 图转文

# 2.22.3
- 😄 新增音乐：suno-v4
- 😄 新增gpt模型：gpt-4o-2024-11-20
# 2.22.2
- 😄 新增：支持ruanway 官方api
- 🐞 修复：模型识图表示

# 2.22.1
- 😄 新增：超链定位tab 定位到可灵 https://vercel.ddaiai.com//#/video/index?tab=kling
- 😄 新增：手机可使用 音乐

# 2.21.10
- 😄 新增：claude-3-5-sonnet-all 模型
- 😄 新增：pika 3个视频效果
- 😄 新增：支持 udio


# 2.21.9
- 😄 新增：mj 默认版本为6.1，填写的有保存下次打开 可以重新载入
- 🐞 修复：默认语言(第一次载入的时候)会根据浏览器语言对应，目前支持 中文简体、英语、中文繁体、法语、俄语、韩语、土耳其语、越南语 如果没在这个列表内则为英语

# 2.21.8
- 😄 新增：flux.1.1-pro 画图模型
- 😄 新增：runway3 支持 参考视频

# 2.21.7
- 😄 新增：claude-3-5-sonnet-20241022 

# 2.21.6
- 😄 新增：pika 文生视频 图生视频
- 🐞 修复：luma 支持长宽比例

# 2.21.5
- 🐞 修复：luam、runway视频删除、viggle删除、kling删除、suno删除？ #510

# 2.21.4
- 😄 新增：runway图片增加首尾帧选择

# 2.21.3
- 🐞 修复：回复数最多只有4096太少导致有时无法正常输出 #516
- 😄 优化：支持实时语音对话服务中的设置

# 2.21.2
- 😄 新增：支持实时语音对话服务 realtime `gpt-4o-realtime-preview`

# 2.21.1
- 😄 优化：dall格式图片本地存储（flex,idemgram 不会图片链接过期而找不到 ）
- 😄 优化：kling图片本地存储

# 2.20.10
- 😄 新增：模型 `o1-preview` `o1-mini`

# 2.20.9
- 🐞 修复：kling 图片提交
- 😄 新增：可灵 kling 的镜头运用

# 2.20.8
- 😄 新增：可灵 kling 视频 绘图模块

# 2.20.7
- 😄 新增：runway 可以 extend
- 🐞 修复：ideogram 清空

# 2.20.6
- 😄 新增： 画图 ideogram 相关模块

# 2.20.5
- 😄 新增： flux 相关模型的dall.e格式
- 🐞 修复：claude-3-5，maxtoken问题 #495

# 2.20.4
- 🐞 修复：更新了背景图版本后。聊天窗口内容上下滚动有时候会失效，要重新刷新页面才能滚动 #490
- 🐞 修复：docker部署能不用在编排的时候填写key

# 2.20.3
- 🤖 合并： 新增自定义背景图片 #488 @Yanyutin753
- 💄 合并： 优化文件上传样式 #487 @Yanyutin753
- 💄 合并： AUTH_SECRET_KEY 新增多密钥支持，使用,隔开 #484 @Yanyutin753 
- 😄 新增： runway Gen3a Turbo
- 😄 新增： UI服务端 同步 `runway` `viggle` 设置

# 2.20.2
- 😄 新增：gemini-1.5-pro-exp-0801
- 😄 新增：chatgpt-4o-latest

# 2.20.1
- 😄 新增：gpt-4o-2024-08-06

# 2.19.10
- 😄 新增：视频 runway gen3 支持图片
- 😄 新增：mj 6.1选项
- 😄 新增：runway-gen3-fast 选项
- 🐞 修复：LUMA_SERVER 出现标签选项

# 2.19.9
- 🐞 修复：luma 说明
- 🐞 修复：Midjourney生图后，保留prompt在输入框中 #468

# 2.19.8
- 🐞 修复：runway 过期.重新获取

# 2.19.7
- 😄 新增：视频 runway 模块
- 🐞 修复：gpt-4o-mini 图片问题
- 🐞 修复：luma 说明
 

# 2.19.6
- 😄 新增：gpt-4o-mini模型
- 🐞 修复：viggle 下载有问题

# 2.19.5
- 🐞 修复：后续会有luma尾帧么 #452
- 😄 新增：viggle pro 跟 relax 能相互切换

# 2.19.4
- 🐞 修复：luma pro 与 relax版本切换 获取任务有问题


# 2.19.3
- 🐞 修复：viggle 个人上传视频无效

# 2.19.2
- 😄 新增：跳舞视频viggle模块

# 2.19.1
- 🐞 修复：Luma下载按钮无法下载？ #443
- 🐞 修复：luma pro 与 relax版本切换 获取任务有问题
- 🐞 修复：suno 歌词 fail 提示，luma 状态 failed 提示

# 2.18.10
- 🐞 修复：视频按钮提示词，有个小错别字。 #424
- 🐞 修复：claude-3-5-sonnet-20240620无法上传图片 #425 #427 #430
- 🐞 修复：LUMA不支持竖屏9:16 这个对于短视频 不友好 官方是支持的 #431
- 🐞 修复：其实cluade其他模型也是支持识图 #433
- 😄 新增：LUMA视频 支持 `延展` 每 `延展` `+5s`
- 😄 修复：LUMA不支持竖屏9:16 这个对于短视频 不友好 官方是支持的 #431

# 2.18.9
- 🐞 修复：luma download_url bug
- 🐞 修复：claude-3-5-sonnet-20240620传图片直接给我调用gpt-4-vision-preview #423

# 2.18.8
- 🐞 修复：无法通过?settings={"key":"{key}","url":"{server}"}设置Suno和Luma #412
- 😄 升级：suno请求带 `/suno` 前缀
- 🐞 修复：请求新增逆向模型 `gpt-4o-all` #400
- 😄 新增： `claude-3-5-sonnet-20240620` 模型
- 🐞 修复：Bug: 手机版Safari下地址栏遮挡界面 #371

# 2.18.7
- 😄 新增：支持luma视频

# 2.18.6
- 😄 升级：suno支持延伸
- 😄 升级：suno支持 以音频生成音频（需要用到延伸）

# 2.18.5
- 😄 升级：将suno可版本选择 v3 v3.5
- 🐞 修复：suno 生成失败 error 状态

# 2.18.4
- 😄 升级：将suno 升级为3.5版本

# 2.18.3
- 🐞 重大修复：修复卡死.第二处

# 2.18.2
- 🐞 重大修复：修复卡死

# 2.18.1
- 🐞 修复：GPTS页面不支持一个页面一个模型 #378
- 😄 新增：GPTs页 可以新增gpts

# 2.17.10 
- 😄 新增：新增自定义可视化模型 #338 参数 `CUSTOM_VISION_MODELS`
- 🐞 修复：Bug: 设置SYSTEM_MESSAGE后模型依然对KnowledgeCutOffDate有误解 #370
- 🐞 修复：Bug: 手机版Safari下地址栏遮挡界面 #371

# 2.17.9 
- 🐞 修复：自定义模型的tokens配置 #362 #333
- 🐞 修复：手机版界面下 MENU_DISABLE 没有生效 #363
- 🐞 修复：绘图的时候自动新建一个对话 #365

# 2.17.8
- 🐞 修复：MJ在等待队列状态下的处理逻辑
- 😄 优化：读图由原来的 `gpt-4-vision-preview`  改为 自定义

# 2.17.7
- 🐞 修复：目前对于公式显示似乎有严重问题 #345 (再次修复)
- 🐞 修复：是否支持已有模型列表的自定义？ #297

# 2.17.6
- 🐞 修复：目前对于公式显示似乎有严重问题 #345
- 🐞 修复：MJ漏掉V6的2个按钮 高清2倍.subtle 高清2倍.creative
- 😄 新增：关于gpts的模型名称传入问题 (支持`g-*`) #334
- 😄 优化：Markdown优化图片显示

# 2.17.5
- 🐞 修复：`gpt-4o`,`gpt-4o-2024-05-13` 截止日期

# 2.17.4
- 🐞 修复：mj放大按钮 有v5变v6
- 😄 新增：`gpt-4o`,`gpt-4o-2024-05-13` 模型

# 2.17.3
- 🐞 修复：左侧菜单栏不显示 #327
# 2.17.2
- 😄 优化：设置服务端设置 填写key 一键同步mj，suno
- 😄 优化：左侧菜单栏可以配置 通过环境变量调整 `MENU_DISABLE="gpts,music,gallery"` #308
- 😄 新增：gemini-pro-1.5 模型 #326
- 😄 优化：`gemini-pro-vision` `gemini-pro-1.5`   `gpt-4-turbo`,`gpt-4-turbo-2024-04-09`  模型 可读base64图 #326

# 2.17.1
- 😄 优化：模型选择可搜索
- 😄 优化：suno错误提示 #305
- 🐞 修复：mj-api-secret 为空时出错 #295
- 🐞 修复：fix CLOSE_MD_PREVIEW #316

# 2.16.10
- 😄 新增：suno音乐 单独模块

# 2.16.9
- 😄 修复：桌面端程序版本问题

# 2.16.8
- 😄 新增：桌面端程序


# 2.16.7
- 😄 新增：新模型 `gpt-4-turbo-2024-04-09`

 
# 2.16.6
- 🐞 修复：手机端不支持 `sref` `cref`
- 😄 新增：`sref` `cref` 上传至discord做为图床 
- 😄 新增：新模型 `suno-v3`

# 2.16.5
- 🐞 修复：nPaint image editor sources availability #248
- 🐞 修复：Bugs in supporing customer models #235

# 2.16.4
- 😄 新增：turnstile 安全认证
- 🐞 修复：模型切换导致模型错乱
- 🐞 修复：访问上传文件需认证

# 2.16.3
- 😄 新增：MJ `cref` `sref` `cw` 参数 
- 🐞 修复：MJ功能问题反馈 #228 
- 🐞 修复：关于余额用量精确度的问题建议 #223
- 🐞 修复：mj 清参数 按钮
- 🐞 修复：更新对话模型 未能更新窗口列表

# 2.16.2
- 😄 新增：MJ `--cref 图片url` 生成角色一致的图像
- 🐞 优化：新开会话模型 每个会话一个自己的模型 #211 #193 

# 2.16.1
- 🐞 修复：头像链接加载很慢 #212
- 🐞 修复：关于模型`claude-3`  `max_tokens` 增加为 4k #214

# 2.15.10
- 🐞 修复：Midjourney Proxy v2.5.5 API后端不接受 index为0的重绘提交 #209 #210 感谢 @hugoshao PR
- 🐞 修复：Drawing 多语言本地化问题  #201 感谢 @hugoshao PR
- 😄 新增：`claude-3-sonnet-20240229` `claude-3-opus-20240229` 而 `claude-3-opus-20240229` 可支持传图 #207

# 2.15.9
- 🐞 修复：聊天记录能导出，但是导入没成功 #197
- 😄 PR：编辑对话内容 感谢 PR人 @bigQY

# 2.15.8
- 🐞 修复：dark模型下的code显示有问题
- 😄 新增：环境变量 `UPLOAD_TYPE` 指定上传方式 ['R2' R2上传] ['API' 跟随UI前端中转]、['Container' 本地容器]、['MyUrl' 自定义链接]   #178
- 😄 调整：MJ默认调整为 `v6`

# 2.15.7
- 🐞 修复：mj提交错误提示 规范化
- 😄 新增：实时语音识别

# 2.15.6
- 🐞 修复：微信绘图弹窗兼容问题 #177 
- 😄 新增：环境变量控制 `CLOSE_MD_PREVIEW=1`，是否开启输入MD预览 #124
- 😄 新增：防爆破验证 相关变量 `AUTH_SECRET_ERROR_COUNT=3` `AUTH_SECRET_ERROR_TIME=10`

# 2.15.5
- 🐞 修复：授权提示 `请重新输入授权访问密码`
- 😄 新增：提交版本信息
- 😄 新增：@触发使用过的GPTs #140

# 2.15.4
- 🐞 修复：mj 上传文件 服务端授权认证( vercel 暂不支持) #157
# 2.15.3
- 🐞 修复：服务端授权认证( vercel 暂不支持) #138

# 2.15.2
- 😄 新增： 输入预览 增加md功能 #124
- 🐞 修复： 更新模型logo未变化 #137
- 😄 新增： 模型 `gpt-3.5-turbo-0125`
- 😄 新增： MJ 模型 `niji V6`

# 2.15.1
- 🐞 修复： tts转化在微信内播放有问题 #126 @yoke1990
- 🐞 修复： 自定义GPTs 在vercel 不可使用 #115
- 🐞 修复： 针对每一个对话分别设置模型无效 #128 感谢
- 🔨 优化： MJ 绘画选项组合优化，减少提示词给mj提示错误 #127 感谢 @yoke1990
- 🔨 优化： 清空同时清空标题 #117  
- 😄 新增： 环境变量主题 `SYS_THEME` 主题 `light`或者`dark` 默认 `dark` ( 新版本需要 清缓存 ) #123


# 2.14.10
- 😄 新增： TTS 人物设置
- 😄 新增： 环境变量 `UPLOAD_IMG_SIZE` #27
- 🔨 优化： GPTs 踩、赞 
- 🔨 优化： 自定义GPTs

# 2.14.9
- 😄 新增： 模型 `gpt-4-0125-preview`

# 2.14.8
- 🐞 修复：垫图图片不能2次使用
- 😄 新增：标头 列表页

# 2.14.7
- 😄 新增： 补回`temperature` 和 `top_p` `presence_penalty` `frequency_penalty`设置  #86
- 😄 优化： 切换模型中  所有设置能随着对话框保存
- 🐞 修复： 默认画图打开 #99

# 2.14.6
- 😄 新增： 语言版本`法语` `土耳其语` 感谢 @M4K4R PR
- 🐞 修复： 手机端token被遮挡  #98
- 🐞 修复： 环境变量 打开wsrv图片图床 `MJ_IMG_WSRV=1`
- 🐞 修复： midjourney图片 wsrv图床 bug

# 2.14.5
- 😄 新增： midjourney wsrv访问图片
# 2.14.4
- 🐞 修复：手机端的页面绘画不出图 #59
- 🐞 修复：midjourney 强制刷新不起作用
# 2.14.3
- 😄 新增： 角色自定到会话 #75 #40
- 😄 新增： 支持one-api部署聊天 https://vercel.ddaiai.com/#/?settings={%22key%22:%22sk-abc%22,%22url%22:%22https://api.openai.com%22}

# 2.14.2
- 🐞 修复： gpt-4-1106-preview 模型 128000 #66
- 😄 新增： 录音whisper转文本对话ChatGPT
- 😄 新增： 对话内容tts转语音
- 😄 新增： 文件上传支持 `cloudflare r2 存储` 感谢 @xuzhenjun130 PR

# 2.14.1
- 🐞 修复： gpt-4-1106-preview 模型 128k #66
- 🐞 修复： 余额显示方式 #61
- 😄 新增： `DISABLE_GPT4=1` 控制不让用 GPT-4 #65
- 😄 新增： `OpenAi Api Key 错误` 对话框中出现引导设置

# 2.13.10
- 🔨 优化： 输入实时计算剩余tokens #63
- 🐞 修复： 重新获取bug

# 2.13.9
- 😄 新增： 超链设置

# 2.13.8
- 🐞 修复： #55 将画图提示词加到2000字
- 🔨 优化： 上传.加入进度条
- 😄 新增： midjourney `清设置`按钮
- 😄 新增： midjourney `自定义变焦`功能


# 2.13.7
- 🐞 修复： #55 名称错误
- 😄 新增： midjourney shorten 操作
- 🐞 修复： 手机端无GPTs入口

# 2.13.6
- 🔨 优化： UI服务端保存
- 😄 新增： 国际化语言包

## 2.13.5
- 🐞 修复： 历史记录未带附件链接
- 😄 新增： 系统通知 #47

## 2.13.4
- 🐞 修复： midjourney 参数不起作用

## 2.13.3
- 😄 更新： 更新本月使用量、余额的请求方式

## 2.13.2 
- 🐞 修复： midjourney 刷新错误
- ✅ 新增： tts whisper 界面支持
- 😄 新增： midjourney 新增 V6


## 2.13.1 
- 🐞 修复： gpts 加载排序
- 😄 新增： google、百度统计
- 😄 新增： 文件支持拖拽上传、粘贴截图上传 #39


## 2.12.11 
- 🐞 紧急修复： gpt-4-vision-preview 格式错误

## 2.12.10 
- 🐞 修复：希望实现左侧绘画功能区固定，不随对话界面上下滚动 #29
- 🐞 修复：当服务端有错误，ui错误显示为空bug 
- 🔨 优化：新增 `CUSTOM_MODELS` 环境变量 可自定义可选模型 #32
 


## 2.12.9 
- 🐞 修复：按住回车不放，会一直触发提交刷新页面 #24
- 🔨 优化：我的画廊 支持来之服务端的数据（适合自建服务器）
- 🔨 优化：midjourney 新增 `原始链接` 按钮

## 2.12.8
- 😄 新增：我的画廊
- 🐞 修复：重试按钮、停止按钮功能 #15


## 2.12.7
- 😄 新增：vercel 增加 AUTH_SECRET_KEY 可以访问输入验证 #15
- 🐞 修复：OPENAI_API_MODEL 默认模型 同时支持 vercel #16
- 🐞 修复：在手机端左侧没法下滑 #18


## 2.12.6
- 🐞 修复：`经常出现“新建聊天框”遮挡对话框的情况 ` #13
- 🐞 修复：当GPTS在绘画窗口，切换不起效果
- 🐞 修复：分页载入GPTs计数出现的问题

## 2.12.5
- 🔨 优化：丰富 GPTS 内容，可以搜索
- 😄 新增：前端UI 设置 上传文件入口 #11
- 🐞 修复：`经常出现“新建聊天框”遮挡对话框的情况 ` #13


## 2.12.4
- 😄 新增 dall-e-2模型
- 🐞 修复：上传错误提示为空
- 🐞 修复：`环境变量中配置的OPENAI_API_BASE_URL和OPENAI_API_KEY依旧没有效果，前端对话一直处于“思考中...”` #4

## 2.12.3
- 😄 新增 支持超链模型切换 http://ip:6013/#/m/gpt-4-all http://ip:6013/#/m/gpt-4-gizmo-1234
- 😄 新增 支持 GPTs 多模态

## 2.12.2
- 😄 新增：支持文件后端上传（供给gpt-4-all gpt-4-gizmo-xxx 模型）！ 默认是关闭的 打开需要环境变量 API_UPLOADER=1
- 😄 新增：支持逆向模型 gpt-4-all gpt-4-v gpt-4-gizmo-(gizmo_id)

## 2.12.1
- 😄 新增：图片上传图片 供gpt-4-vision-preview使用
- 🐞 修复:：midjourney 辅助提示“模型版本” 去掉早期过时版本

## 2.11.10
- 🐞 修复：dall-e-3的大小规格
- 😄 新增：gpt模型选择
- 😄 新增：gpt自定义模型、上下文数、回复数
- 🔩 更改：流请求方式由原来的axios改为fetch 打字效果更加顺滑

## 2.11.9 
- 😄 新增：dall-e-3 画图 
## 2.11.8
- 🐞 修复：midjourney 辅助提示“性格” 出现的bug
- 😄 新增：最新版本检查
- 😄 新增：midjourney 获取seed

## 2.11.7
- 😀 新增：midjourney 换脸
- 😀 新增：midjourney 混图