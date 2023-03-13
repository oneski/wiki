---
id: getting-started
title: वॉलेट
sidebar_label: Getting Started
description: समर्थित वॉलेट की एक सूची प्राप्त करें और की कार्यनीति का प्रबंधन करें.
keywords:
  - wiki
  - polygon
  - wallet
  - integrate
  - guide
image: https://wiki.polygon.technology/img/polygon-wiki.png
---

:::tip नई जानकारी लेते रहें

हमारी [<ins>नोटिफ़िकेशन</ins>](https://polygon.technology/notifications/) की सदस्यता देकर पॉलीगॉन टीम और समुदाय से नवीनतम वॉलेट सूट अपडेट के साथ रखें.

:::

पॉलीगॉन का समर्थन करने वाले वॉलेट की प्रबंधन, निजी की द्वारा नियंत्रित अकाउंट के एक्सेस
और इंटरफ़ेस की अनुमति देते हैं जो यूज़र्स को चेन पर कार्यवाई करने और ट्रांज़ैक्शन पर हस्ताक्षर करने की अनुमति देते हैं.
निम्नलिखित पेज पॉलीगॉन के साथ कॉम्पैटिबल वॉलेट के लिए एक वॉलेट इंडेक्स के रूप में कार्य करता है. कृपया ध्यान दें
कि यह एक सम्पूर्ण इंडेक्स नहीं है.

:::caution थर्ड पार्टी वॉलेट

इन थर्ड पार्टी वॉलेट में पॉलीगॉन को एकीकृत किया गया है और ये विभिन्न सुविधाओं का समर्थन करते हैं.
**उनका इस्तेमाल करने से पहले आप अपना ही काम करें**. आधिकारिक पॉलीगॉन
समर्थन इन वॉलेट या अन्य non-native वॉलेट के साथ मुद्दों के लिए सहायता प्रदान नहीं कर सकता है.

:::

:::info विकेंद्रित एक्स्चेंज (CEXs)

पॉलीगॉन का समर्थन करने वाले CEXs की सूची के लिए, किसी थर्ड पार्टी ट्रैकिंग वेबसाइट पर जाएं जैसे कि
[<ins>**CoinMarketCap**</ins>](https://coinmarketcap.com/currencies/polygon/markets). कैप

:::

## नेटिव वॉलेट {#native-wallets}

[पॉलीगॉन सपोर्ट](https://support.polygon.technology/support/home) उपयोगकर्ताओं को सहायता प्रदान कर सकता है और निम्नलिखित वॉलेट से संबंधित मुद्दों को पता चलता है:

| वॉलेट | कस्टडी | अकाउंट प्रकार | मल्टी-सिग | dapp ब्राउज़र | प्लेटफ़ॉर्म |
|----------------------------------------------------------------------|---------------|--------------|-----------|--------------|----------|
| [पॉस वॉलेट](https://wallet.polygon.technology/login/) | गैर-कस्टोडियल | eoa | नहीं | नहीं | ब्राउज़र |
| [Hermez वॉलेट](https://wallet.hermez.io/login) | गैर-कस्टोडियल | eoa | नहीं | नहीं | ब्राउज़र |
| [Avail Apps (टेस्टनेट)](https://devnet-avail.polygon.technology/) | बिना कस्टडी वाले | eoa | हाँ | नहीं | ब्राउज़र |


## पार्टनर वॉलेट {#partner-wallets}

निम्नलिखित वॉलेट ऐसे समाधान हैं जिनके साथ पॉलीगॉन टेक्नोलॉजी ने भागीदारी की है:

| वॉलेट | कस्टडी | अकाउंट प्रकार | मल्टी-सिग | NFT | dapp ब्राउज़र | ब्रिज सहायता | फाइऐट ऑन-रैंप | प्लेटफ़ॉर्म |
|---	|---	|---	|---	|---	|---	|---	|---	|---	|
| [1इंच](https://1inch.io/wallet/) | गैर-कस्टोडियल | eoa | नहीं | इंटरफ़ेस | हाँ | हाँ | हाँ | मोबाइल |
| [अल्फा वॉलेट](https://alphawallet.com/) | बिना कस्टडी वाले | eoa | नहीं | इंटरफ़ेस | हाँ | हाँ | हाँ | मोबाइल, api/sdk |
| [अटॉमिक वॉलेट](https://atomicwallet.io/)* | गैर-कस्टोडियल | eoa | नहीं | नहीं | नहीं | नहीं | हाँ | मोबाइल , डेस्कटॉप, api/sdk |
| [Ambire](https://www.ambire.com/) | गैर-कस्टोडियल | स्मार्ट कॉन्ट्रैक्ट | नहीं | इंटरफ़ेस | नहीं | हाँ | हाँ | ब्राउज़र |
| [BitKeep](https://bitkeep.com/) | गैर-कस्टोडियल | eoa | नहीं | इंटरफ़ेस | हाँ | हाँ | हाँ | मोबाइल, ब्राउज़र एक्सटेंशन |
| [Bitski](https://www.bitski.com/) | कस्टोडियल | eoa | नहीं | इंटरफ़ेस | नहीं | हाँ | नहीं | ब्राउज़र, api/sdk |
| [Coin98](https://coin98.com/wallet) | गैर-कस्टोडियल | eoa | नहीं | इंटरफ़ेस | हाँ | हाँ | हाँ | मोबाइल ब्राउज़र, api/sdk |
| [Coinbase](https://www.coinbase.com/wallet) | हाइब्रिड | eoa | नहीं | इंटरफ़ेस | हाँ | हाँ | हाँ | मोबाइल ब्राउज़र, api/sdk |
| [CypherD](https://cypherd.io/) | गैर-कस्टोडियल | eoa | नहीं | हाँ | हाँ | हाँ | हाँ | मोबाइल |
| [D'Cent](https://dcentwallet.com/) | हाइब्रिड | eoa | नहीं | इंटरफ़ेस | हाँ | हाँ | नहीं | मोबाइल |
| [Exodus](https://www.exodus.com/) | बिना कस्टडी वाले | eoa | नहीं | हाँ | नहीं | नहीं | हाँ | मोबाइल , डेस्कटॉप |
| [Gnosis सेफ](https://gnosis-safe.io/) | बिना कस्टडी वाले | स्मार्ट कॉन्ट्रैक्ट | हाँ | इंटरफ़ेस | नहीं | नहीं | नहीं | मोबाइल, ब्राउज़र, डेस्कटॉप, api/sdk |
| [Guarda](https://guarda.com/) | गैर-कस्टोडियल | eoa | नहीं | नहीं | नहीं | हाँ | हाँ | मोबाइल ब्राउज़र, डेस्कटॉप |
| [Huobi](https://www.itoken.com/en) | गैर-कस्टोडियल | eoa | नहीं | हाँ | हाँ | हाँ | नहीं | मोबाइल |
| [लेजर](https://www.ledger.com/) | बिना कस्टडी वाले | eoa | नहीं | इंटरफ़ेस | नहीं | नहीं | हाँ | हार्डवेयर, मोबाइल, डेस्कटॉप |
| [Loopring](https://loopring.io/#/) | गैर-कस्टोडियल | स्मार्ट कॉन्ट्रैक्ट | नहीं | नहीं | नहीं | नहीं | नहीं | मोबाइल, api/sdk |
| [Magic](https://fortmatic.com/)* | कस्टोडियल | eoa | नहीं | नहीं | नहीं |   |   | मोबाइल ब्राउज़र, api/sdk |
| [MathWallet](https://mathwallet.org/en-us/) | कस्टोडियल | eoa | नहीं | नहीं | नहीं | हाँ | हाँ | मोबाइल ब्राउज़र, api/sdk |
| [मेटामास्क](https://metamask.io/)* | गैर-कस्टोडियल | eoa | नहीं | इंटरफ़ेस | हाँ | नहीं | नहीं | मोबाइल ब्राउज़र, api/sdk |
| [Multis](https://multis.co/)* | गैर-कस्टोडियल | eoa | नहीं | नहीं | नहीं |   | हाँ | मोबाइल , डेस्कटॉप |
| [MyEtherWallet](https://www.myetherwallet.com/)* | गैर-कस्टोडियल | eoa | नहीं | इंटरफ़ेस | नहीं |   | हाँ | मोबाइल |
| [ओमनी](https://omni.app/) | बिना कस्टडी वाले | eoa | नहीं | इंटरफ़ेस | नहीं | हाँ |   | मोबाइल, api/sdk |
| [ओपेरा क्रिप्टो ब्राउज़र](https://www.opera.com/crypto/next)* | गैर-कस्टोडियल | eoa | नहीं | सहायता | हाँ |   |   | मोबाइल, ब्राउज़र |
| [पिलर](https://www.pillar.fi/) | गैर-कस्टोडियल | eoa | नहीं | इंटरफ़ेस | नहीं |   | हाँ | मोबाइल |
| [रेनबो](https://rainbow.me/) | गैर-कस्टोडियल | eoa | नहीं | इंटरफ़ेस | हाँ |   | नहीं | मोबाइल, api/sdk |
| [SafePal](https://safepal.io/) | बिना कस्टडी वाले | eoa | नहीं | नहीं | हाँ | हाँ |   | हार्डवेयर, मोबाइल, api/sdk |
| [सीक्वेंस](https://sequence.app/auth) | गैर-कस्टोडियल | स्मार्ट कॉन्ट्रैक्ट | नहीं | इंटरफ़ेस | नहीं |   |   | ब्राउज़र, api/sdk |
| [SimpleHold](https://simplehold.io/) | गैर-कस्टोडियल | eoa | हाँ | नहीं | नहीं |   | हाँ | मोबाइल, api/sdk |
| [TokenPocket](https://www.tokenpocket.pro/en) | गैर-कस्टोडियल | eoa | नहीं | सहायता | हाँ | हाँ | हाँ | मोबाइल ब्राउज़र, api/sdk |
| [टोरस](https://toruswallet.io/) | गैर-कस्टोडियल | eoa | हाँ | सहायता | नहीं | नहीं | नहीं | ब्राउज़र, api/sdk |
| ट्रेजर | बिना कस्टडी वाले | eoa | नहीं | सहायता | नहीं |   |   | हार्डवेयर, मोबाइल |
| [वॉलेट पर भरोसा करें](https://trustwallet.com/) | बिना कस्टडी वाले | eoa | नहीं | सहायता | हाँ |   | हाँ | मोबाइल |
| [Unstoppable](https://unstoppable.money/) | गैर-कस्टोडियल | eoa | नहीं | हाँ | हाँ |   | नहीं | मोबाइल, api/sdk |
| [Venly](https://www.venly.io/) | हाइब्रिड | स्मार्ट कॉन्ट्रैक्ट | नहीं | इंटरफ़ेस | नहीं |   |   | ब्राउज़र, api/sdk |
| [Wirex](https://wirexapp.com/en/wirex-wallet)* | गैर-कस्टोडियल | eoa | हाँ | नहीं | नहीं |   |   | मोबाइल |
| [XDeFi](https://www.xdefi.io/) | गैर-कस्टोडियल | eoa | नहीं | इंटरफ़ेस | नहीं | नहीं | नहीं | ब्राउज़र |
| [Zerion](https://zerion.io/) | गैर-कस्टोडियल | eoa | नहीं | हाँ | हाँ | हाँ |   | मोबाइल, ब्राउज़र |

:::caution नॉन- देशी वॉलेट सपोर्ट

उपरोक्त तालिका में * के साथ दर्शाए गए वॉलेट मूल रूप से वॉलेट सॉफ़्टवेयर के साथ समर्थित नहीं हैं
और इन्हें पॉलीगॉन नेटवर्क में जोड़ने के लिए मैनुअल स्टेप्स की आवश्यकता होती है.

:::

## की प्रबंधन कार्यनीति {#key-management-strategy}

निम्नलिखित बुनियादी स्टेप्स पॉलीगॉन के साथ क्लाइंट-साइड एप्लिकेशन के एकीकरण की अनुमति देते हैं:

1. **Web3 सेटअप करें**: [web3।js](https://web3js.readthedocs.io/) एक Javascript लाइब्रेरी है जो
क्लाइंट-साइड ऐप्लिकेशन को ब्लॉकचेन से इंटरैक्ट करने के लिए अनुमति देती है. हम संवाद करने के लिए वेब3.js कॉन्फ़िगर करें कम्यूनिकेट करने के लिए web3 कॉन्फ़िगर करते हैं. अपने प्रोजेक्ट में `web3.js` को जोड़ना सीखने के लिए [web3.js डॉक्यूमेंट](https://web3js.readthedocs.io/en/v1.2.2/getting-started.html#adding-web3-js) का इस्तेमाल करें.
2. **एक अकाउंट को सेट करें**: आप Account: भेज सकेंगे (विशेष रूप से जो लोग जो उस को बदल देते हैं. ब्लॉकचेन की स्टेट को बदलते हैं).
3. **कॉन्ट्रैक्ट को इंस्टैंट करें**: एक बार एक वेब 3 ऑब्जेक्ट को जगह पर रखा जाता है, हम अपने तैनात कॉन्ट्रैक्ट को अगले इंस्टैंट करें जिसके साथ हमें इंटरैक्ट करना है.
4. **कॉल फंक्शन्स** हमारे कॉन्ट्रैक्ट ऑब्जेक्ट के जरिए कॉन्ट्रैक्ट में फंक्शन के जरिए डेटा ले लो.