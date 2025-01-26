想要调用OpenAI的API接口，但不知道如何开始？本教程详细介绍了如何绑定银行卡、申请API Key以及通过手机号验证，为你提供从申请到验证的一站式解决方案。

## 0. 注意事项

在将银行卡绑定到OpenAI之前，请确保卡内至少有5美元余额。若没有此金额，绑定将会失败。此外，务必通过美国家庭网络环境进行操作，使用普通代理网络可能会导致绑定过程出错。

## 1. 安装浏览器插件

建议查看 [野卡注册教程](https://bit.ly/bewildcard)，填写邀请码：ACCPAY，这样可以获得开卡优惠。

## 2. 登录 OpenAI 平台

开启浏览器，访问 [platform.openai.com](https://platform.openai.com)。接着，输入你的OpenAI账号和密码，这就是你的ChatGPT账号。

## 3. 绑定付款方式

登录后，点击左侧的“Settings -> billing”选项，选择“Add payment details”来添加你的支付信息。

- 若想直接跳到此步骤，可以访问 [账单概览](https://platform.openai.com/account/billing/overview)。
- 接下来，选择“Set up paid account”，根据需求选择个人使用或公司使用。
- 输入卡号、有效期、CVV和邮政编码，并填写你的姓名和野卡提供的账单地址，完成后点击“continue”。
- 绑定成功后，系统会让你选择充值金额，金额范围为5至50美元。充值后，你就可以直接使用GPT-4的API了。
- 你还可以设置自动充值，例如，如果余额低于5美元，系统会自动从绑定的卡中扣款10美元进行充值。

## 4. 申请 API Key

在菜单中找到“API Keys”，可以查看已创建的API密钥和添加新密钥的按钮。你也可以直接通过 [创建API Keys](https://platform.openai.com/api-keys) 创建新的API密钥。

- 点击“Start verification”开始验证过程，这要求一个海外手机号码。
- 前往 [野卡](https://bit.ly/bewildcard)，申请一个“海外手机号”，并复制得到的手机号。
- 在选择国家时，记得选择英国（United Kingdom），然后将手机号粘贴到OpenAI注册页面的输入框中，点击“发送验证码”。
- 刷新野卡页面，查看验证码并复制到OpenAI的页面上进行验证。

若验证码未收到或提示手机号已注册，请再申请新的手机号。通常试3个号码，至少会有一个能稳定接收到验证码。

验证成功后，页面会有提示。请注意，一个海外手机号只能用于验证两个API。如果同一手机号再次验证，可能会提示已绑定过一个API，但这不影响使用。

## 5. API 消费额度和扣费

OpenAI会根据充值金额设定消费上限。例如，若充值5美元，则在使用API时最多消费5美元。

若连续两次扣款失败（例如卡内余额不足），OpenAI会锁定该开发者账号和相关卡号。

作为开发者，你可以随时在 [API使用情况](https://platform.openai.com/usage) 查看消费情况，同时在 [调用额度限制](https://platform.openai.com/account/limits) 查看调用额度限制和可用模型，例如GPT-3.5或GPT-4。

👉 [野卡 | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)