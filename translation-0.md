[http://wp.tutsplus.com/tutorials/theme-development/creating-a-wordpress-theme-from-static-html-preparing-the-markup/](http://wp.tutsplus.com/tutorials/theme-development/creating-a-wordpress-theme-from-static-html-preparing-the-markup/)

昨年、私は他のWordPressの開発者の間で小さな調査を行いました。
私が知りたいと思ったは、開発者たちが、最初のWordPressのテーマを構築した時、どのように行うのか？ということです。
既存のテーマをハックする方法だったのか、それとも、静的なHTMLから作り、それをテーマに変えたのか？

私は2番めのアプローチを使うために、多くの人々に話を聞きました。
彼らは、HTMLやCSSを使用してサイトを構築していた、経験豊富なフロントエンドの開発者であり、
彼らは、既存のHTMLファイルを取得し、テーマに変換するのが最も簡単だという事を発見していました。
さらに私は、講師や教師だったという人々から、「これは学生に対してのアプローチである」ということを教わりました。

そのため、このシリーズではその方法を紹介するつもりです。
あなたは、（スタイルシート付きの）単一のHTMLファイルから、複数のテンプレートファイルと、様々なフックにそれらをまわし、
関数、テンプレートタグ、ループを使用して、メニューやウェジェットなどにインクルードされます。

この最初のチュートリアルでは、後のシリーズで我々がカバーすることとなる、テーマ用のPHPに変換する前の、htmlファイルを準備する方法を説明します。