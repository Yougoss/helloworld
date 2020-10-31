# coding: utf-8
"""
@author: xly
@file: helloworld
@time: 2020/10/31 9:25 AM

"""
import tornado.ioloop
import tornado.web


class MainHandler(tornado.web.RequestHandler):
    def get(self):
        self.write("Hello, world")


if __name__ == "__main__":
    app = tornado.web.Application([(r"/", MainHandler)])
    app.listen(9000)
    tornado.ioloop.IOLoop.instance().start()
