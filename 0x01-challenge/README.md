fix my code

. Server status
#advanced
I just started a new Flask project and the first thing I’m putting in place is a route for the status of my API (super important for a load balancer implementation).

But I don’t know why it’s not working…

Could you look at it and fix it please?

My code is here

$ python -m api.v1.app 
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
....
$ curl -XGET http://0.0.0.0:5000/api/v1/status
{
  "error": "Not found"
}
$
