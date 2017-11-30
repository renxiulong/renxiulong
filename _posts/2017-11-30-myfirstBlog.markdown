---
title: my first blog
---

def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
~~~ html
<a href="#">Hello world</a>
~~~
~~~ python
    def parse(self):
        lat = 122.21
        lng = 45.23
        print('lat:'+lat + ' lng:'+lng)
~~~
`​`` html
<a href="#">Hello world</a>
`​``
