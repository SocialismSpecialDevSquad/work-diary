# work-diary
work diary

# android mobile terminal spider system 

# architecture

## 1. python

## 2. mitmproxy + celery + appium     

    control ---> appium
    mitmproxy ---> base flow init crawl_item and capsule a task to send redis crawl task queue
    celery ---> parser the data(json) check data integrity & data persistence
    monitor ---> send event tracking to database
