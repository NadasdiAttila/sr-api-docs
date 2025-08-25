# CMS Content List Extend Resource

## Properties

<ResourceProperties :resource="'cms_content_list_extend'" :lang="'en'"/>

<ResourceScopes :resource="'cms_content_list_extend'"/>

## Endpoints

[//]: <> (GET ENDPOINT)
<ResourceEndpoint :resource="'cms_content_list_extend'" :endpoint="'get'" :lang="'en'">

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/cms_content_list_extend/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/cms_content_list_extend/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (GETCOLLECTION ENDPOINT)
<ResourceEndpoint :resource="'cms_content_list_extend'" :endpoint="'getCollection'" :lang="'en'">

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/cms_content_list_extend/response/json/get_page.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/cms_content_list_extend/response/xml/get_page.xml

</template>

</ResourceEndpoint>

[//]: <> (POST ENDPOINT)
<ResourceEndpoint :resource="'cms_content_list_extend'" :endpoint="'post'" :lang="'en'">

<template v-slot:request>

<<< @/docs/fixtures/api/cms_content_list_extend/request/post.json

</template>

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/cms_content_list_extend/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/cms_content_list_extend/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (PUT ENDPOINT)
<ResourceEndpoint :resource="'cms_content_list_extend'" :endpoint="'put'" :lang="'en'">

<template v-slot:request>

<<< @/docs/fixtures/api/cms_content_list_extend/request/put.json

</template>

<template v-slot:responseJSON>

<<< @/docs/fixtures/api/cms_content_list_extend/response/json/get_id.json

</template>

<template v-slot:responseXML>

<<< @/docs/fixtures/api/cms_content_list_extend/response/xml/get_id.xml

</template>

</ResourceEndpoint>

[//]: <> (DELETE ENDPOINT)
<ResourceEndpoint :resource="'cms_content_list_extend'" :endpoint="'delete'" :lang="'en'"/>
