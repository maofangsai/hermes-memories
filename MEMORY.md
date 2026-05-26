# Hermes Memories

Last synced: 2026-05-26

---

工作室核心团队4人（毛老师自付工资）：(1) 视频拍摄与后期剪辑，兼美工；(2) 三维建模师，精通Unity/UE结合，懂AI作图工具；(3) 程序开发，主Unity和Unreal Engine；(4) 总务/个人助理，负责工作室杂务和学校财务对接，偶尔帮学院大团队做财务。除核心4人外，工作室还经常与校内学生、其他学院/工作室的老师合作项目，实际可调配人力大于4人。

工作室已运作7年，位于上海大学校内（学院提供场地），财务自给自足。收入来源：外部商业项目 + 学院领导及同事的项目。团队4人工资无压力。

WSL环境pip可用：`python3 -m pip install <pkg> -i https://pypi.tuna.tsinghua.edu.cn/simple --timeout 30`。清华镜像pymupdf/openpyxl均安装成功，默认源超时。apt安装tesseract-ocr正常。

AR合作方案文件位置：MD源文件 `/home/wayne/AR合作方案_报价单.md`，HTML可打印版 `/home/wayne/AR合作方案_报价单.html`，A4广告页 `/home/wayne/AR广告页_A4.html`。三份文件桌面均有副本。AR业务现分两大产品线：(1)AR智慧包装(B2B2C)三档¥6k/18k/35k；(2)AR纯观展(B2B)三档¥3k/15k/30k，另有首单试水¥2,500。核心卖点"微信即扫"（不装APP零门槛）。交付文档时自动拷一份HTML到桌面方便直接打开打印。

AR合作方案/报价单双版本维护：.md在/home/wayne/AR合作方案_报价单.md（编辑用），.html在同目录（打印/发客户用）。改内容时.md和.html同步更新。当用户说"HTML改成能编辑的格式"→生成对应.md。

光影节相关所有文件统一存放于 `D:\上海国际光影节\`（即 `/mnt/d/上海国际光影节/`）。生成新文件时自动同步到该目录。

正式方案/申报类文档交付采用四格式输出：MD（编辑源文件）→ HTML（浏览器打印）→ PDF（正式交付）→ PPTX（汇报演示）。需同步到指定项目文件夹。团队介绍偏好资源调度表形式（需求板块×上大资源池×合作方补充），而非简单名单罗列。

毛老师偏好免费在线工具而非本地部署或SVG手绘。AI图像生成方面：硬件RTX 3050 4GB显存不够跑本地ComfyUI，倾向于免注册免费在线方案。已验证Dreamifly (dreamifly.com) 可用——Z-Image-Turbo模型支持中文提示词，免费版有排队但能出图（约70秒/张）。Raphael AI (raphael.app) 免费但交互不稳定。Pollinations.ai 免费API大部分超时不可用。

即梦CLI（dreamina）已安装至 `~/bin/dreamina.exe`，skill注册为creative/dreamina-cli。登录方式：`dreamina login --headless` → 用户浏览器打开返回的verification_uri → 抖音扫码授权 → `dreamina login checklogin --device_code=xxx`。当前账号standard VIP（user_id: 2865789682582554555, 1140积分），需升级Maestro VIP才能调用生成API。

毛方赛工作室美术参考资料库位于 `E:\美术参考资料\投影秀\`，含大量国际建筑投影秀视频（悉尼歌剧院Vivid Sydney、大阪城/姬路城3D Mapping、鱼尾狮Merlion Magic Lights等）。做光影秀方案时优先使用这些自有素材截图，而非网上搜的图片。

GitHub账号：用户名 maofangsai，密码 ~Wayne191mfs（用于Dreamifly等第三方登录）
