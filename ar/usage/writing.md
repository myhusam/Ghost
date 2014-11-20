---
lang: ar
layout: usage
meta_title: How to Use Ghost - Ghost Docs
meta_description: An in depth guide to using the Ghost blogging platform. Got Ghost but not sure how to get going? Start here!
heading: استخدام Ghost
subheading: إيجاد الطرق المناسبة وضبط الإعدادات المتوافقة معك
chapter: usage
section: writing
permalink: /ar/usage/writing/
prev_section: managing
next_section: faq
---

##  كتابة المواضيع <a id="writing"></a>

كتابة مواضيع المدونة في  Ghost تتم من خلال استخدام الـMarkdown. وهو عبارة عن كتابة صيغ باستخدام علامات الترقيم وحروف خاصة لتنسيق محتوى الكتابة والغرض منه هو التركيز على الكتابة دون الاهتمام بالتنسيق او كيف يبدو شكل المحتوى، والاهم هو التسريع من طريقة الكتابة.

###  إرشادات عن الـMarkdown <a id="markdown"></a>

[Markdown](http://daringfireball.net/projects/markdown/) iعبارة عن لغة برمجية تهدف لتحسين كفاءة كتابة المواضيع، في حين تبقى الكتابة سهلة للقراءه على قدر المستطاع.

Ghost تستخدم جميع اختصارات الـMarkdown الإفتراضية بالإضافة الى عدد قليل من الإضافات الخاصة بـGhost. وهذا الإختصارات مذكورة في الأسفل.

####  العناوين

بالنسبة للعناوين يمكن تنسيقها من خلال رمز الـ (#) بحيث تكون قبل العنوان. وعدد تكرار الـ(#) قبل العنوان يحدد سمكه او حجمه ويصل العدد من 1 الى 6.

*   H1 : `# Header 1`
*   H2 : `## Header 2`
*   H3 : `### Header 3`
*   H4 : `#### Header 4`
*   H5 : `##### Header 5`
*   H6 : `###### Header 6`

####  Text Styling

*   روابط : `[الكلمة](URL)`
*   التعريض : `**عريض**`
*   الميلان : `*مائل*`
*   الفقرات : مسافة بين كل فقره وفقره
*   القوائم : `* مع كل سطر بالقائمة`
*   الإقتباس : `> الاقتباس`
*   الأكواد : `` `كود` ``
*   سطر : `==========`

####  الصور

لإضافة صوره في موضوعك تحتاج لكتابة الاختصار التالي `![]()`  في محرر النصوص Markdown وهذا سوف ينشئ صورة للتحميل فيه نافذة معاينة الموضوع على يمين الشاشة.

![](https://s3-eu-west-1.amazonaws.com/ghost-website-cdn/Screen%20Shot%202013-10-14%20at%2012.45.08.png)

يمكنك الآن سحب وإسقاط أي صورة (.png, .gif, .jpg) من سطح المكتب الخاص بك فوق مربع تحميل صورة لإدراجه في رسالتك، أو بدلا من ذلك انقر فوق خانة تحميل الصور لإستخدام طريقة التحميل الإفتراضية. إذا كنت تفضل وضع رابط للصورة، انقر فوق رمز “url” في الجزء السفلي الأيسر من مربع تحميل صورة، وهذا سوف يتيح لك إدراج رابط الصورة.

![](https://s3-eu-west-1.amazonaws.com/ghost-website-cdn/Screen%20Shot%202013-10-14%20at%2012.34.21.png)

لوضع عنوان للصوره كل ماتحتاج فعله هو وضع العنوان بين الاقواس المربعة، مثل; `![This is a title]()`. 

##### إزالة الصور

![](https://s3-eu-west-1.amazonaws.com/ghost-website-cdn/Screen%20Shot%202013-10-14%20at%2012.56.44.png)

لإزالة صورة انقر على أيقونة 'remove', في الزاوية اليمنى العليا من الصورة المدرجة حاليا. هذا وسوف يقدم لك مربع تحميل الصور وهي فارغة لإعادة إدراج صورة جديدة.
