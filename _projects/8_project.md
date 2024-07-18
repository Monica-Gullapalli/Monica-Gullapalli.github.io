---
layout: page
title: PortFolio Pulse
description: A Django based financial Portfolio webapp that allows users to track their investments and manage their portfolios
img: assets/img/9.jpg
importance: 2
category: work
giscus_comments: true
---

A django tech stack web application that allows users to maintain a record of their investments in stocks and crypto Currencies also 

    ---
    link: https://github.com/Monica-Gullapalli/PortfolioPulse-Django-WebApp.git
    ---


# Final Project Links

- [Final Deployment](http://gullapallimonica.pythonanywhere.com/usignup/)
- [Final Github Repo](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20.git)
- [Final User Stories](https://trello.com/b/DeGjB8FM/fseportfoliopulse)
- [Final Overview Page](https://github.com/coloradocollective/5828_S24/wiki/Team-20:-PortfolioPulse)
- [Final PPT](https://docs.google.com/presentation/d/14DMFWzqRrVgIF8F3mQoO-nuW8QUgIT5BpIQsqe7xXz8/edit?usp=sharing)


# Rubric Items

| Topic | Links to the Code | Comments |
|:-----|:----------------:|:---------:|
| Web application basic form, reporting | [Link](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/tree/main/fin_app/templates) | Includes SignUp, login, create Stock investments form, create crypto investments form etc |
| Data collection | [Link](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/tree/main/collector_app) | Fetches data from the API in accordance with data entered by user in fin_app |
| Data analyzer | [Link](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/tree/main/analyzer_app) | Performs visualization on updating data in the database from collector app functions along with entered data in fin_app using matplotlib |
| Unit tests | [Link](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/blob/main/fin_app/tests.py) | Test_usignup_view, test_ulogin_view, test_ulogout_view, test_home_view, test_create_view, test_view_view, test_create_crypto_view and more |
| Data persistence any data store | [Link 1](http://gullapallimonica.pythonanywhere.com/admin/login/?next=/admin/) and [Link 2](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/blob/main/db.sqlite3) | Efficient to view using /admin in Django apps |
| Rest collaboration internal or API endpoint | [Link](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/blob/main/collector_app/templatetags/yfinance_tags.py) | Used yfinance API or Yahoo Finance API to fetch close_price of stock |
| Product environment | [Link](http://gullapallimonica.pythonanywhere.com/usignup/) | PythonAnywhere is our deployment platform |
| Integration tests | [Link](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/blob/main/analyzer_app/tests.py) | Test_stock_graph_no_stocks, test_invalid_stock_data and more |
| Using mock objects or any test doubles | [Link](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/blob/main/fin_app/tests.py) | Line 301 to 318 |
| Continuous integration | [Link]([(https://blog.pythonanywhere.com/87/)]) | Created a bare repo while deployment in pythonanywhere, wont show on github actions so attached link to the process followed |
| Production monitoring instrumenting | [Link](https://www.pythonanywhere.com/user/GullapalliMonica/webapps/#tab_id_gullapallimonica_pythonanywhere_com) | URL only accessible to developer, but images have been included in presentation for proof |
| Acceptance tests | [Link](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/blob/main/acceptance_tests/acc_tests.py) | Test_user_signup, test_user_login, test_user_logout using selenium |
| Event collaboration messaging | [Link](https://github.com/CSCI-5828-S24/Fse-finalproject-Group20/blob/main/financial_project/settings.py) | From line number 139-147 |
| Continuous delivery | [Link]([(https://blog.pythonanywhere.com/87/)]) | Created a bare repo while deployment in pythonanywhere, wont show on github actions so attached link to the process followed |



<br/>
<br/>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Shows UI of the Application
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Image showing fetched stocks/cryptos
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

If you want to explore more about the project or view it on your computer locally:

{% raw %}

```html
git clone https://github.com/Monica-Gullapalli/PortfolioPulse-Django-WebApp.git
pip install -r requirements.txt
django manage.py startapp
```

{% endraw %}
