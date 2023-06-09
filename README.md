<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

nodejs၊ [direnv](https://direnv.net) ၊ [bun ကို](https://github.com/oven-sh/bun) ဦးစွာထည့်သွင်းရန် အကြံပြုထားပြီး၊ ထို့နောက် လမ်းညွှန်ကိုဝင်ရောက်ပြီးနောက် `direnv allow` (လမ်းညွှန်ကိုဝင်ရောက်ပြီးနောက် [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ကို အလိုအလျောက်လုပ်ဆောင်လိမ့်မည်)။

အဓိပ္ပာယ်မှာ- ဂျပန်၊ ကိုးရီးယား၊ အင်္ဂလိပ်၊ အင်္ဂလိပ်၊ အခြားဘာသာစကားအားလုံးသို့ တရုတ်ဘာသာပြန်။ သင်သည် တရုတ်နှင့် အင်္ဂလိပ်တို့ကိုသာ ပံ့ပိုးလိုပါက `zh: en` သာ ရေးနိုင်သည်။

အဓိပ္ပါယ်မှာ- ဂျပန်၊ ကိုးရီးယား၊ အင်္ဂလိပ်၊ အင်္ဂလိပ်၊ အခြားဘာသာစကားအားလုံးသို့ တရုတ်ဘာသာပြန်။ သင်သည် တရုတ်နှင့် အင်္ဂလိပ်တို့ကိုသာ ပံ့ပိုးလိုပါက `zh: en` သာ ရေးနိုင်သည်။

* [ရှေ့ဆုံးကုဒ်](https://github.com/xxai-art/web)
* [ဆိုက်တစ်ခုလုံးအတွက် ဘာသာစကားအစုံအလင်](https://github.com/xxai-art/web/tree/main/i18n)
* [လော့ဂ်အင်မော်ဂျူးများအတွက် ဘာသာစကား packs](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Website Multilingual Documentation](https://github.com/xxai-doc)

ရှေ့ဆုံးပရိုဂရမ်းမင်းဘာသာစကားမှာ [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) ဖြစ်ပြီး ကော်ဖီခရစ်အထားအသိုကိုအခြေခံ၍ အချို့သောအင်္ဂါရပ်များကို ပေါင်းထည့်သည့် [./coffee_plus.md](./coffee_plus.md) ကို ကြည့်ပါ။

## ဝဘ်ဆိုဒ်များနှင့် စာရွက်စာတမ်းများကို နိုင်ငံတကာသို့ ပြောင်းလဲခြင်း။

အောက်ပါ ပရောဂျက် ၃ ခုကို တည်ဆောက်ပါ။

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  suffix သည် `.mdt` ဖြစ်သည်၊ သင်သည် ပြင်ပဖိုင်များကိုရည်ညွှန်းရန် `<+ ./coffee_plus/import.js>` နှင့် ဆင်တူသော syntax ကိုသုံးနိုင်ပြီး `.md` ၏ နောက်ဆက်တွဲဖြင့် အမှတ်အသားလုပ်ပါ။

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Markdown ဘာသာပြန်ခြင်းသည် ကုဒ်များနှင့် လင့်ခ်များကို ဘာသာပြန်မည်မဟုတ်ဘဲ ဘာသာပြန်ထားသော စာကြောင်းများကို ကက်ရှ်လုပ်ပါမည်။ ဘာသာပြန်ဆိုခြင်းကို ပြုပြင်ထားသော်လည်း မူရင်းစာသားကို ပြုပြင်မွမ်းမံပါက၊ ၎င်းကို ထပ်မံလုပ်ဆောင်ပါက ဘာသာပြန်ဆိုချက်၏ ပြုပြင်မွမ်းမံမှုကို ထပ်ရေးမည်မဟုတ်ပါ။

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` ထုတ်လုပ်ထားသော ဝဘ်ဆိုဒ်များကို ဘာသာပြန်ဆိုခြင်းအတွက် ဘာသာစကားဖိုင်များ။

### Document Translation Automation Instructions

ကုဒ် repository [xxai-art/doc ကို](https://github.com/xxai-art/doc) ကြည့်ပါ။

nodejs၊ [direnv](https://direnv.net) ၊ [bun ကို](https://github.com/oven-sh/bun) ဦးစွာထည့်သွင်းရန် အကြံပြုထားပြီး၊ ထို့နောက် လမ်းညွှန်ကိုဝင်ရောက်ပြီးနောက် `direnv allow` (လမ်းညွှန်ကိုဝင်ရောက်ပြီးနောက် [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ကို အလိုအလျောက်လုပ်ဆောင်လိမ့်မည်)။

ဘာသာစကားရာပေါင်းများစွာသို့ ဘာသာပြန်ဆိုထားသော ကုဒ်အခြေခံကြီးများကို ရှောင်ရှားရန်အတွက်၊ ကျွန်ုပ်သည် ဘာသာစကားတစ်ခုစီအတွက် သီးခြားကုဒ်အခြေခံတစ်ခုကို ဖန်တီးပြီး ကုဒ်အခြေခံကို သိမ်းဆည်းရန် အဖွဲ့အစည်းတစ်ခုကို ဖန်တီးခဲ့သည်။

ပတ်ဝန်းကျင် ပြောင်းလဲနိုင်သော `GITHUB_ACCESS_TOKEN` သတ်မှတ်ပြီးနောက် [create.github.coffee ကို](https://github.com/xxai-art/doc/blob/main/create.github.coffee) အသုံးပြုခြင်းသည် ကုဒ်သိုလှောင်မှုအား အလိုအလျောက် ဖန်တီးပေးမည်ဖြစ်သည်။

ဟုတ်ပါတယ်၊ သင်ကုဒ်အခြေခံထဲမှာလည်းထည့်နိုင်ပါတယ်။

ဘာသာပြန်ဇာတ်ညွှန်း ကိုးကား [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

ဇာတ်ညွှန်းကုဒ်ကို အောက်ပါအတိုင်း ဘာသာပြန်ဆိုထားပါသည်။

[bunx](https://bun.sh/docs/cli/bunx) သည် ပိုမြန်သော npx ကို အစားထိုးသည်။ သေချာပါတယ်၊ သင့်မှာ bun မတပ်ဆင်ထားဘူးဆိုရင်၊ သင်အစား `npx` သုံးနိုင်ပါတယ်။

`bunx mdt zh` သည် `.mdt` `.md` အဖြစ် zh directory တွင် ပြန်ဆိုသည်၊ အောက်တွင် လင့်ခ်ချိတ်ထားသော ဖိုင် 2 ခုကို ကြည့်ပါ

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` သည် ဘာသာပြန်ခြင်းအတွက် အဓိကကုဒ်ဖြစ်သည် (သင့်တွင် `nodejs` သာ ထည့်သွင်းထားသော်လည်း `bun` နှင့် `direnv` ထည့်သွင်းမထားပါက၊ ဘာသာပြန်ရန် `npx i18n` ကိုလည်း သုံးနိုင်သည်)။

၎င်းသည် [i18n.yml ကို](https://github.com/xxai-art/doc/blob/main/i18n.yml) ခွဲခြမ်းစိပ်ဖြာမည်ဖြစ်ပြီး၊ ဤစာတမ်းရှိ `i18n.yml` ၏ဖွဲ့စည်းပုံသည် အောက်ပါအတိုင်းဖြစ်သည်-

```
en:
zh: ja ko en
```

အဓိပ္ပာယ်မှာ- ဂျပန်၊ ကိုးရီးယား၊ အင်္ဂလိပ်၊ အင်္ဂလိပ်၊ အခြားဘာသာစကားအားလုံးသို့ တရုတ်ဘာသာပြန်။ သင်သည် တရုတ်နှင့် အင်္ဂလိပ်တို့ကိုသာ ပံ့ပိုးလိုပါက `zh: en` သာ ရေးနိုင်သည်။

နောက်ဆုံးတစ်ခုမှာ [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) ဖြစ်ပြီး၊ ပင်မခေါင်းစဉ်နှင့် ဘာသာစကားတစ်ခုစီ၏ `README.md` ၏ ပထမစာတန်းစာတန်းကြားရှိ အကြောင်းအရာကို `README.md` တွင် ထည့်သွင်းဖော်ပြရန်ဖြစ်သည်။ ကုဒ်သည် အလွန်ရိုးရှင်းသည်၊ သင်ကိုယ်တိုင်ကြည့်ရှုနိုင်သည်။

Google API ကို အခမဲ့ ဘာသာပြန်ရန် အသုံးပြုပါသည်။ အကယ်၍ သင်သည် Google ကို ဝင်သုံး၍မရပါက၊ ကျေးဇူးပြု၍ ကျေးဇူးပြု၍ သတ်မှတ်ပြီး ပရောက်စီကို သတ်မှတ်ပါ-၊

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

ဘာသာပြန်ဇာတ်ညွှန်းသည် `.i18n` လမ်းညွှန်တွင် ဘာသာပြန်ထားသော ကက်ရှ်တစ်ခုကို ထုတ်ပေးမည်ဖြစ်ပြီး၊ ကျေးဇူးပြု၍ ၎င်းကို `git status` ဖြင့် စစ်ဆေးပြီး ထပ်ခါတလဲလဲ ဘာသာပြန်ခြင်းများကို ရှောင်ရှားရန် ၎င်းကို ကုဒ်သိုလှောင်မှုတွင် ထည့်ပါ။

ကက်ရှ်ကို အပ်ဒိတ်လုပ်ရန် ဘာသာပြန်ဆိုချက်ကို မွမ်းမံသည့်အခါတိုင်း `bunx i18n` ကို ဖွင့်ပါ။

မူရင်းစာသားနှင့် ဘာသာပြန်ဆိုချက်အား တစ်ချိန်တည်းတွင် မွမ်းမံထားပါက၊ ကက်ရှ်သည် ရှုပ်ထွေးသွားမည်၊ ထို့ကြောင့် သင်မွမ်းမံလိုပါက၊ သင်တစ်ဦးတည်းသာ ပြင်ဆင်နိုင်ပြီး ကက်ရှ်ကို မွမ်းမံရန်အတွက် `bunx i18n` ကို လုပ်ဆောင်ပါ။
