2022-12-16T21:28:53.664984+00:00 app[web.1]: /app/server/node_modules/stripe/lib/Error.js:38

2022-12-16T21:28:53.664999+00:00 app[web.1]:         return new StripeInvalidRequestError(rawStripeError);

2022-12-16T21:28:53.665000+00:00 app[web.1]:                ^

2022-12-16T21:28:53.665002+00:00 app[web.1]: 

2022-12-16T21:28:53.665003+00:00 app[web.1]: StripeInvalidRequestError: Invalid URL: undefined/success?session_id={CHECKOUT_SESSION_ID}. URLs must begin with http or https.

2022-12-16T21:28:53.665004+00:00 app[web.1]:     at StripeError.generate (/app/server/node_modules/stripe/lib/Error.js:38:16)

2022-12-16T21:28:53.665006+00:00 app[web.1]:     at res.toJSON.then.StripeAPIError.message (/app/server/node_modules/stripe/lib/StripeResource.js:190:35)

2022-12-16T21:28:53.665006+00:00 app[web.1]:     at process.processTicksAndRejections (node:internal/process/task_queues:95:5) {

2022-12-16T21:28:53.665006+00:00 app[web.1]:   type: 'StripeInvalidRequestError',

2022-12-16T21:28:53.665007+00:00 app[web.1]:   raw: {

2022-12-16T21:28:53.665008+00:00 app[web.1]:     code: 'url_invalid',

2022-12-16T21:28:53.665008+00:00 app[web.1]:     doc_url: 'https://stripe.com/docs/error-codes/url-invalid',

2022-12-16T21:28:53.665009+00:00 app[web.1]:     message: 'Invalid URL: undefined/success?session_id={CHECKOUT_SESSION_ID}. URLs must begin with http or https.',

2022-12-16T21:28:53.665009+00:00 app[web.1]:     param: 'success_url',

2022-12-16T21:28:53.665010+00:00 app[web.1]:     request_log_url: 'https://dashboard.stripe.com/test/logs/req_9q3A0w6Atmamb9?t=1671226133',

2022-12-16T21:28:53.665010+00:00 app[web.1]:     type: 'invalid_request_error',

2022-12-16T21:28:53.665010+00:00 app[web.1]:     headers: {

2022-12-16T21:28:53.665011+00:00 app[web.1]:       server: 'nginx',

2022-12-16T21:28:53.665011+00:00 app[web.1]:       date: 'Fri, 16 Dec 2022 21:28:53 GMT',

2022-12-16T21:28:53.665011+00:00 app[web.1]:       'content-type': 'application/json',

2022-12-16T21:28:53.665012+00:00 app[web.1]:       'content-length': '394',

2022-12-16T21:28:53.665012+00:00 app[web.1]:       connection: 'keep-alive',

2022-12-16T21:28:53.665012+00:00 app[web.1]:       'access-control-allow-credentials': 'true',

2022-12-16T21:28:53.665014+00:00 app[web.1]:       'access-control-allow-methods': 'GET, POST, HEAD, OPTIONS, DELETE',

2022-12-16T21:28:53.665014+00:00 app[web.1]:       'access-control-allow-origin': '*',

2022-12-16T21:28:53.665015+00:00 app[web.1]:       'access-control-expose-headers': 'Request-Id, Stripe-Manage-Version, X-Stripe-External-Auth-Required, X-Stripe-Privileged-Session-Required',

2022-12-16T21:28:53.665016+00:00 app[web.1]:       'access-control-max-age': '300',

2022-12-16T21:28:53.665016+00:00 app[web.1]:       'cache-control': 'no-cache, no-store',

2022-12-16T21:28:53.665016+00:00 app[web.1]:       'idempotency-key': '80173508-cf20-42c8-9999-68744a225dce',

2022-12-16T21:28:53.665016+00:00 app[web.1]:       'original-request': 'req_9q3A0w6Atmamb9',

2022-12-16T21:28:53.665017+00:00 app[web.1]:       'request-id': 'req_9q3A0w6Atmamb9',

2022-12-16T21:28:53.665017+00:00 app[web.1]:       'stripe-version': '2022-11-15',

2022-12-16T21:28:53.665017+00:00 app[web.1]:       'strict-transport-security': 'max-age=63072000; includeSubDomains; preload'

2022-12-16T21:28:53.665018+00:00 app[web.1]:     },

2022-12-16T21:28:53.665018+00:00 app[web.1]:     statusCode: 400,

2022-12-16T21:28:53.665018+00:00 app[web.1]:     requestId: 'req_9q3A0w6Atmamb9'

2022-12-16T21:28:53.665018+00:00 app[web.1]:   },

2022-12-16T21:28:53.665019+00:00 app[web.1]:   rawType: 'invalid_request_error',

2022-12-16T21:28:53.665019+00:00 app[web.1]:   code: 'url_invalid',

2022-12-16T21:28:53.665019+00:00 app[web.1]:   doc_url: 'https://stripe.com/docs/error-codes/url-invalid',

2022-12-16T21:28:53.665019+00:00 app[web.1]:   param: 'success_url',

2022-12-16T21:28:53.665019+00:00 app[web.1]:   detail: undefined,

2022-12-16T21:28:53.665020+00:00 app[web.1]:   headers: {

2022-12-16T21:28:53.665020+00:00 app[web.1]:     server: 'nginx',

2022-12-16T21:28:53.665020+00:00 app[web.1]:     date: 'Fri, 16 Dec 2022 21:28:53 GMT',

2022-12-16T21:28:53.665021+00:00 app[web.1]:     'content-type': 'application/json',

2022-12-16T21:28:53.665021+00:00 app[web.1]:     'content-length': '394',

2022-12-16T21:28:53.665021+00:00 app[web.1]:     connection: 'keep-alive',

2022-12-16T21:28:53.665021+00:00 app[web.1]:     'access-control-allow-credentials': 'true',

2022-12-16T21:28:53.665022+00:00 app[web.1]:     'access-control-allow-methods': 'GET, POST, HEAD, OPTIONS, DELETE',

2022-12-16T21:28:53.665022+00:00 app[web.1]:     'access-control-allow-origin': '*',

2022-12-16T21:28:53.665022+00:00 app[web.1]:     'access-control-expose-headers': 'Request-Id, Stripe-Manage-Version, X-Stripe-External-Auth-Required, X-Stripe-Privileged-Session-Required',

2022-12-16T21:28:53.665022+00:00 app[web.1]:     'access-control-max-age': '300',

2022-12-16T21:28:53.665023+00:00 app[web.1]:     'cache-control': 'no-cache, no-store',

2022-12-16T21:28:53.665023+00:00 app[web.1]:     'idempotency-key': '80173508-cf20-42c8-9999-68744a225dce',

2022-12-16T21:28:53.665023+00:00 app[web.1]:     'original-request': 'req_9q3A0w6Atmamb9',

2022-12-16T21:28:53.665023+00:00 app[web.1]:     'request-id': 'req_9q3A0w6Atmamb9',

2022-12-16T21:28:53.665024+00:00 app[web.1]:     'stripe-version': '2022-11-15',

2022-12-16T21:28:53.665024+00:00 app[web.1]:     'strict-transport-security': 'max-age=63072000; includeSubDomains; preload'

2022-12-16T21:28:53.665024+00:00 app[web.1]:   },

2022-12-16T21:28:53.665024+00:00 app[web.1]:   requestId: 'req_9q3A0w6Atmamb9',

2022-12-16T21:28:53.665025+00:00 app[web.1]:   statusCode: 400,

2022-12-16T21:28:53.665025+00:00 app[web.1]:   charge: undefined,

2022-12-16T21:28:53.665025+00:00 app[web.1]:   decline_code: undefined,

2022-12-16T21:28:53.665026+00:00 app[web.1]:   payment_intent: undefined,

2022-12-16T21:28:53.665026+00:00 app[web.1]:   payment_method: undefined,

2022-12-16T21:28:53.665026+00:00 app[web.1]:   payment_method_type: undefined,

2022-12-16T21:28:53.665027+00:00 app[web.1]:   setup_intent: undefined,

2022-12-16T21:28:53.665027+00:00 app[web.1]:   source: undefined

2022-12-16T21:28:53.665027+00:00 app[web.1]: }