---
id: getting-started
title: Bắt đầu
permalink: docs/getting-started.html
next: add-react-to-a-website.html
redirect_from:
  - "docs/"
  - "docs/index.html"
  - "docs/getting-started-ko-KR.html"
  - "docs/getting-started-zh-CN.html"
  - "docs/installation.html"
  - "download.html"
  - "downloads.html"
  - "docs/try-react.html"
  - "docs/tooling-integration.html"
  - "docs/package-management.html"
  - "docs/language-tooling.html"
  - "docs/environments.html"
---
 
Trang này là tổng quan về tài liệu React và các tài nguyên liên quan.

**React** là một thư viện JavaScript để xây dựng giao diện người dùng. Tìm hiểu những gì React có tất cả trong [trang chủ](/) của chúng tôi hoặc trong [hướng dẫn](/tutorial/tutorial.html).

---

- [Thử với React](#try-react)
- [Học React](#learn-react)
- [Thông tin nội bộ](#staying-informed)
- [Phiên bản tài liệu](#versioned-documentation)
- [Có thể thiếu gì đó?](#something-missing)

## Thử với React {#try-react}

React đã được thiết kế từ đầu để áp dụng dần dần và **bạn có thể sử dụng ít hoặc nhiều React như bạn cần.** Cho dù bạn muốn thử React, hãy thêm một số tương tác vào một trang HTML đơn giản hoặc bắt đầu một ứng dụng hỗ trợ React phức tạp, các liên kết trong phần này sẽ giúp bạn bắt đầu.

### Viết code react trực tuyến {#online-playgrounds}

Nếu bạn thích viết code React, bạn có thể sử dụng một trình soạn mã trực tuyến. Hãy thử mẫu Hello World trên  [CodePen](codepen://hello-world), [CodeSandbox](https://codesandbox.io/s/new), hoặc [Glitch](https://glitch.com/edit/#!/remix/starter-react-template).

Nếu bạn thích sử dụng trình soạn thảo văn bản của riêng mình, bạn cũng có thể [tải file HTML này](https://raw.githubusercontent.com/reactjs/reactjs.org/master/static/html/single-file-example.html) , chỉnh sửa nó và mở nó từ hệ thống tập tin cục bộ trong trình duyệt của bạn. Nó thực hiện chuyển đổi mã thời gian chạy chậm, vì vậy chúng tôi chỉ khuyên bạn nên sử dụng mã này cho các bản demo đơn giản.

### Thêm React vào website {#add-react-to-a-website}

Bạn có thể [thêm React vào trang HTML trong một phút](/docs/add-react-to-a-website.html). Sau đó, bạn có thể dần dần mở rộng sự hiện diện của nó hoặc giữ nó trong một vài khối động.

### Tạo một ứng dụng React mới {#create-a-new-react-app}

Khi bắt đầu một dự án React, [một trang HTML đơn giản với các thẻ script](/docs/add-react-to-a-website.html) vẫn có thể là lựa chọn tốt nhất. Chỉ mất một phút để thiết lập!

As your application grows, you might want to consider a more integrated setup. There are [several JavaScript toolchains](/docs/create-a-new-react-app.html) we recommend for larger applications. Each of them can work with little to no configuration and lets you take full advantage of the rich React ecosystem.

## Learn React {#learn-react}

People come to React from different backgrounds and with different learning styles. Whether you prefer a more theoretical or a practical approach, we hope you'll find this section helpful.

* If you prefer to **learn by doing**, start with our [practical tutorial](/tutorial/tutorial.html).
* If you prefer to **learn concepts step by step**, start with our [guide to main concepts](/docs/hello-world.html).

Like any unfamiliar technology, React does have a learning curve. With practice and some patience, you *will* get the hang of it.

### First Examples {#first-examples}

The [React homepage](/) contains a few small React examples with a live editor. Even if you don't know anything about React yet, try changing their code and see how it affects the result.

### React for Beginners {#react-for-beginners}

If you feel that the React documentation goes at a faster pace than you're comfortable with, check out [this overview of React by Tania Rascia](https://www.taniarascia.com/getting-started-with-react/). It introduces the most important React concepts in a detailed, beginner-friendly way. Once you're done, give the documentation another try!

### React for Designers {#react-for-designers}

If you're coming from a design background, [these resources](https://reactfordesigners.com/) are a great place to get started.

### JavaScript Resources {#javascript-resources}

The React documentation assumes some familiarity with programming in the JavaScript language. You don't have to be an expert, but it's harder to learn both React and JavaScript at the same time.

We recommend going through [this JavaScript overview](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript) to check your knowledge level. It will take you between 30 minutes and an hour but you will feel more confident learning React.

>Tip
>
>Whenever you get confused by something in JavaScript, [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript) and [javascript.info](https://javascript.info/) are great websites to check. There are also [community support forums](/community/support.html) where you can ask for help.

### Practical Tutorial {#practical-tutorial}

If you prefer to **learn by doing,** check out our [practical tutorial](/tutorial/tutorial.html). In this tutorial, we build a tic-tac-toe game in React. You might be tempted to skip it because you're not building games -- but give it a chance. The techniques you'll learn in the tutorial are fundamental to building *any* React apps, and mastering it will give you a much deeper understanding.

### Step-by-Step Guide {#step-by-step-guide}

If you prefer to **learn concepts step by step,** our [guide to main concepts](/docs/hello-world.html) is the best place to start. Every next chapter in it builds on the knowledge introduced in the previous chapters so you won't miss anything as you go along.

### Thinking in React {#thinking-in-react}

Many React users credit reading [Thinking in React](/docs/thinking-in-react.html) as the moment React finally "clicked" for them. It's probably the oldest React walkthrough but it's still just as relevant.

### Recommended Courses {#recommended-courses}

Sometimes people find third-party books and video courses more helpful than the official documentation. We maintain [a list of commonly recommended resources](/community/courses.html), some of which are free.

### Advanced Concepts {#advanced-concepts}

Once you're comfortable with the [main concepts](#main-concepts) and played with React a little bit, you might be interested in more advanced topics. This section will introduce you to the powerful, but less commonly used React features like [context](/docs/context.html) and [refs](/docs/refs-and-the-dom.html).

### API Reference {#api-reference}

This documentation section is useful when you want to learn more details about a particular React API. For example, [`React.Component` API reference](/docs/react-component.html) can provide you with details on how `setState()` works, and what different lifecycle methods are useful for.

### Glossary and FAQ {#glossary-and-faq}

The [glossary](/docs/glossary.html) contains an overview of the most common terms you'll see in the React documentation. There is also a FAQ section dedicated to short questions and answers about common topics, including [making AJAX requests](/docs/faq-ajax.html), [component state](/docs/faq-state.html), and [file structure](/docs/faq-structure.html).

## Staying Informed {#staying-informed}

The [React blog](/blog/) is the official source for the updates from the React team. Anything important, including release notes or deprecation notices, will be posted there first.

You can also follow the [@reactjs account](https://twitter.com/reactjs) on Twitter, but you won't miss anything essential if you only read the blog.

Not every React release deserves its own blog post, but you can find a detailed changelog for every release [in the `CHANGELOG.md` file in the React repository](https://github.com/facebook/react/blob/master/CHANGELOG.md), as well as on the [Releases](https://github.com/facebook/react) page.

## Versioned Documentation {#versioned-documentation}

This documentation always reflects the latest stable version of React. Since React 16, you can find older versions of the documentation [on a separate page](/versions). Note that documentation for past versions is snapshotted at the time of the release, and isn't being continuously updated.

## Something Missing? {#something-missing}

If something is missing in the documentation or if you found some part confusing, please [file an issue for the documentation repository](https://github.com/reactjs/reactjs.org/issues/new) with your suggestions for improvement, or tweet at the [@reactjs account](https://twitter.com/reactjs). We love hearing from you!
