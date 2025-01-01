---
layout: "ssg-theme-astro/layouts/main.astro" # This line of code should remain unchanged.
tag: "GTM-5TR7XX4"
title: "Royal Cuisine 御食坊 - Best Food Today"
favicon: "favicon.ico"
logo: "logo.jpg"
primaryColor: "#633710" # logo color
secondaryColor: "#ffe22f"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "light"
cuid: ""
ruid: ""
orderOnlineLink: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=314fa88b-c585-42d0-b4f9-fea6871d00cb"
tableReservationLink: "https://www.bestfoodtodayus.com/ordering/restaurant/menu/reservation?restaurant_uid=314fa88b-c585-42d0-b4f9-fea6871d00cb&reservation=true&client_is_mobile=true"
tel: "408-777-8989"

# banner:
#   text:
#     # - boldText: "🥳 Special Offer"
#     - boldText: "20% off cash discount"
#     - text: " on xxx"
#     - smText: ""
#   # add more text...
#   textColor: "#ffffff"
#   bgColor: "#E7383D"
#   bgOpacity: "1" # 0~1

# header
header:
  logoSize: 55
  logoSizeOnMobile: 40
  textAfterLogo:
    text: ""
    size: 16
    color: ""
  showTextAfterLogoOnMobile: false
  bgColor: "#ffffff"
  bgOpacity: "1" # 0~1
  menuTextColor: "#000000"
  menu:
    - { text: "首页", link: "/zh-cn" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "关于我们", link: "#about-us" }
    - { text: "联系我们", link: "#contact-us" }
    - { text: "English", link: "/" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"

  otherBtn1InsteadText: "在线订餐"
  otherBtn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=314fa88b-c585-42d0-b4f9-fea6871d00cb"
  otherBtn2InsteadText: ""
  otherBtn2Href: ""

sections:
  # hero
  - type: "hero"
    id: ""
    height: "80" # Conditionally use only when sectionType is imgBg
    sectionType: "imgBg" # video | imgWithText | imgBg
    bgVideoType: "gjw" # youtube | vimeo | gjw
    bgVideoId: "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
    bgImg: "Royal Cuisine 御食坊01.webp"
    bgColor: "#000000"
    bgOpacity: "0.5" # 0~1
    title:
      - "Royal Cuisine"
      - "御食坊"
    titleColor: "#ffffff"
    description:
      - "提供正宗的川菜和东北菜"
    descriptionColor: "#ffffff"
    # title2:
    #   - ""
    # title2Color: "#ffffff"
    # description2:
    #   - ""
    # description2Color: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""

    btn1Text: "在线订餐"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=314fa88b-c585-42d0-b4f9-fea6871d00cb"
    btn2Text: "餐桌预定"
    btn2Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu/reservation?restaurant_uid=314fa88b-c585-42d0-b4f9-fea6871d00cb&reservation=true&client_is_mobile=true"

    bannerImg: "sample.webp"
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"

  # # Video
  #   - type: "video"
  #     id: ""
  #     title:
  #       - "Lorem ipsum dolor sit amet"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et"
  #     videoType: "gjw" # vimeo | gjw | youtube
  #     videoId:
  #       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
  #       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
  #     isOnlyDisplayOnMobile: false

  # Gallery  - Menu
  - type: "gallery"
    id: "gallery"
    mode: 4 # 1 - 4
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "Royal Cuisine"
      - "御食坊的菜品"
    titleColor: "#000000"
    description:
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # textBlock - only title
  - type: "textBlock"
    id: "about-us"
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "关于我们"
    titleColor: "#000000"
    description:
      - "欢迎光临 Royal Cuisine 御食坊！我们提供正宗的中国菜。老板娘 Kelly 在湾区经营各类餐馆已有20多年的经验。她的川菜和东北菜广为人知。Royal Cuisine 御食坊是两种菜系的完美结合。"
    descriptionColor: ""

  # Gallery  - Welcome To Royal Cuisine 御食坊
  - type: "gallery"
    id: ""
    mode: 4 # 1 - 4
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "欢迎光临"
      - "Royal Cuisine 御食坊"
    titleColor: "#000000"
    description:
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery2"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # # feature - imgWithText
  #   - type: "feature"
  #     noMarginTop: true
  #     id: ""
  #     height: "100" # Conditionally use only when sectionType is imgBg
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     title:
  #       - "Lorem ipsum dolor sit ame"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     descriptionColor: "#000000"

  #     addOrderOnlineBtn: false
  #     orderOnlineBtnInsteadText: ""
  #     addTableReservationBtn: false
  #     tableReservationBtnInsteadText: ""

  #     btn1Text: ""
  #     btn1Href: ""
  #     btn2Text: ""
  #     btn2Href: ""

  #     bannerImg: "sample.webp"
  #     imgPosition: "imgLeft" # imgLeft | imgRight
  #     bannerMarginTopMobile: 20
  #     imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # # feature - map
  #   - type: "feature"
  #     id: ""
  #     noMarginTop: false
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     title:
  #       - "Store 2 : Washington St"
  #     titleColor: "#000000"
  #     description:
  #       - "Opening Hours: "
  #       - "Mon-Fri 8:30 AM-8:00 PM, Sat-Sun 9:00 AM-8:30 PM"
  #     descriptionColor: "#000000"

  #     addOrderOnlineBtn: true
  #     orderOnlineBtnInsteadText: ""
  #     addTableReservationBtn: true
  #     tableReservationBtnInsteadText: ""
  #     showOtherBtn: true
  #     btn1Text: "Order online from Washington St Store"
  #     btn1Href: "#"
  #     btn2Text: ""
  #     btn2Href: ""

  #     map: true
  #     url: "https://maps.app.goo.gl/HDDb5yFih4S8TmDe7"
  #     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d197.0491990412703!2d-122.4063506!3d37.7950269!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085815e4be59617%3A0x87622e118f7e38a2!2sHon%E2%80%99s%20Wun-Tun%20House!5e0!3m2!1sen!2sjp!4v1722232541079!5m2!1sen!2sjp"
  #     addTelBtn: true
  #     tel: "12345678"
  #     telInsteadText: "Call: (123) 456-7890"
  #     tel2: "876543210" # if there are two phone numbers"
  #     tel2InsteadText: "Call: (876) 543-2100"
  #     getDirectionBtnInsteadText: ""
  #     imgPosition: "" # imgLeft | imgRight

  # # textBlock
  #   - type: "textBlock"
  #     id: "about-us"
  #     bgImg: ""
  #     bgColor: ""
  #     bgOpacity: "" # 0~1
  #     title:
  #       - "About Us"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     descriptionColor: "#000000"

  # textBlock - Information
  - type: "textBlock"
    noMarginTop: false
    id: ""
    bgImg: "/Royal Cuisine 御食坊08.webp"
    bgColor: "#000"
    bgOpacity: "0.6" # 0~1
    title:
      - "新功能! 在线订餐"
    titleColor: "#ffffff"
    description:
      - "现在支援线上订单自取。只要告诉我们您想要的菜肴，我们会​​尽快准备好。所有订单都由我们手动确认。您可以即时查看您的食物何时准备好。订单状态会即时更新，您可以在萤幕上查看您的食物何时可以取走。"
    descriptionColor: "#ffffff"

  # map
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/jC8UAF8epGG6xNsb8"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3173.1187642640207!2d-122.03625052413788!3d37.31601437210453!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fb52bfbf34cef%3A0x4dc9f4418eea4275!2z5b6h6aOf5Z2KLeS7pOS6uuS4iueYvueahOehheiwt-S4nOWMl-iPnC_lt53oj5w!5e0!3m2!1szh-CN!2sjp!4v1723099695585!5m2!1szh-CN!2sjp"
    addTelBtn: true
    tel: ""
    telInsteadText: "电话：408-777-8989"
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: "前往餐厅"

#  # The modal will only appear once within 30 minutes."
#   - type: "modal"
#     bgColor: "#333"
#     bgOpacity: "0.1" # 0~1
#     title:
#       - "🎁 Special Offers"
#     titleColor: "#FF2D2F"
#     titleSize: 24
#     description:
#       - "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     descriptionColor: ""
#     descriptionSize: 16
#     imgName: "special_offer.webp"
#     imgAlt: "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     imgHref: ""
#     buttonText: ""

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: ""
  bgColor: "#f3f4f6"
  bgOpacity: "1" # 0~1
  textColor: "#000000" # default white

  openingHoursInsteadText: "付款方式"
  openingHours:
    - "周一 ～ 周四"
    - "11:00 AM - 3:00 PM, 4:30 PM - 9:30 PM"
    - "周五"
    - "11:00 AM - 3:00 PM, 4:30 PM - 10:00 PM"
    - "周六 ～ 周日"
    - "11:00 AM - 10:00 PM"

  isLogo: true
  logoSize: 75
  logoSizeOnMobile: 45

  # menu:
  #   - { text: "Home", link: "/" }
  #   - { text: "Gallery", link: "#gallery" }
  #   - { text: "About Us", link: "/#about-us" }
  #   - { text: "Contact Us", link: "/#contact-us" }
  #   - { text: "中文", link: "/zh-cn" }

  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""

  acceptedPaymentMethodsInsteadText: "付款方式"
  paymentMethod: "visa,amex,cash,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  addressInsteadText: "地 址"
  address:
    - address: "10477 S De Anza Blvd, Cupertino, CA 95014"
      url: "https://maps.app.goo.gl/jC8UAF8epGG6xNsb8"

  # at a minimum, please make sure to include the meta description.
seo:
  metaTitle: "Royal Cuisine 御食坊｜圣荷西｜中餐厅"
  metaDescription: "位于加州圣荷西萨拉托加大道1312号的一家中餐厅，提供江苏和浙江菜肴。我们提供外卖和送餐服务。"
  img: "Royal Cuisine 御食坊01.webp"
  thisPageUrl: "https://royalcuisine-order.com/zh-cn"
  locale: "zh_CN" # zh_TW | zh_CN
  canonicalHref: "https://royalcuisine-order.com/zh-cn"
---

<!-- hello world -->
