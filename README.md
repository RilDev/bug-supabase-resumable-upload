# Supabase: Reusmable Upload Not Working.

## Message to the support team

We are trying to use Supabase's resumable upload feature as describe here: https://supabase.com/blog/storage-v3-resumable-uploads

Right now, we get an error every time we try to access the `/storage/v1/upload/resumable` endpoint.

```
POST https://project-id.supabase.co/storage/v1/upload/resumable 404 (Not Found)
```

I saw in this thread that we needed to contact the support in order to enable this functionality. https://github.com/supabase/supabase/issues/14754#issuecomment-1783993688

## How to start the project

Launch dev server: `npx http-server`

You'll also need to provide an anon-key and a project ID.

Thanks for your help!
