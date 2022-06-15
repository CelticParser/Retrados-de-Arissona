
## Firebase

```
firebase login
firebase deploy --only hosting
```

---

## Cloudinary API

API/Secret: 411528374683961:PXtF8M992HzFH4DLJzZAL6jWeiw

~~~
curl https://411528374683961:PXtF8M992HzFH4DLJzZAL6jWeiw@mo-api.cloudinary.com/v1/retratosdearissona/ping
~~~

### Cache Warmup

~~~
curl https://411528374683961:PXtF8M992HzFH4DLJzZAL6jWeiw@mo-api.cloudinary.com/v1/retratosdearissona/cache_warm_up -X POST --data 'url=https://retratosdearissona.mo.cloudinary.net/img/La-Mision-de-San-Xavier-del-Bac.jpg?tx=t_complex'
~~~