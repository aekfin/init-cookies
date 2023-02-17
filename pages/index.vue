<template>
  <Tutorial />
</template>

<script>
export default {
  name: 'IndexPage',
  mounted () {
    const a = 'accessToken=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJvbV9pZCI6OCwiZGV2aWNlX2lkIjoiMTY3NjYxMTI1Njk1OCIsInJvbGVfaWQiOjYsInJvbGVfaWRfbGlzdCI6WzEsMiwzLDYsNyw4LDksMTEsMTIsMTMsMTQsMThdLCJpbnN0cnVjdG9yX2lkIjpudWxsLCJwcm92aWRlcl9pZCI6MTMxLCJpc19sb2dpbl9hcyI6bnVsbCwiaWF0IjoxNjc2NjExNDQ5LCJleHAiOjE2NzY5MTE0NDl9.Ouw4uqmUUA4XVdWbZ1VD8oaGxzV74AexoljbwN1F2Y'
    const b = 'refreshToken=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJvbV9pZCI6OCwiZGV2aWNlX2lkIjoiMTY3NTgzMzA0MjA2OCIsInJvbGVfaWQiOjEsInJvbGVfaWRfbGlzdCI6WzEsMiwzLDYsNyw4LDksMTEsMTIsMTMsMTRdLCJpbnN0cnVjdG9yX2lkIjpudWxsLCJwcm92aWRlcl9pZCI6bnVsbCwiaXNfbG9naW5fYXMiOm51bGwsImlhdCI6MTY3NjQ4MTA5OSwiZXhwIjoxNjc3MzgxMDk5fQ.5wYUefS3iCkQgMu6B7MPA4QdxN3vqVOpBLnDB6VmkzQ'
    const c = 'sessionid=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJvbV9pZCI6OCwiZGV2aWNlX2lkIjoiZGY3OTRmNjItNjgwYS00ZDdlLWI4MjEtM2VkYmZmYjdmOTUwIiwicm9sZV9pZCI6MSwicm9sZV9pZF9saXN0IjpbMSwyLDMsNiw3LDgsOSwxMSwxMiwxMywxNCwxOF0sImluc3RydWN0b3JfaWQiOm51bGwsInByb3ZpZGVyX2lkIjpudWxsLCJpc19sb2dpbl9hcyI6bnVsbCwiaWF0IjoxNjc2NjEzODgzLCJleHAiOjE2NzY5MTM4ODN9.65ZjiP-iG2A8E8lQGkrwIjbbpf1vYT_tm5MC01ba0Uw'
    const d = 'csrftoken=qzQKqJvzZygQIGMt4GaeGnpwJnIWK6leK1A5kMtUEhDIo5NF4i9CwAzaJWVHJ2b'
    document.cookie = `${a}; ${b}; ${c}; ${d};`
    console.log(document.cookie)
  }
}
</script>
