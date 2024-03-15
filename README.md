# test-guide
1. Create an account in https://zammad.eyecos.org/
2. Go to http://5.75.148.51:3001/ and add yourself to Pro or Family Plan
3. Check your email for the invitation link
4. Verify yourself is pro by going to https://zammad.eyecos.org/
5. Click on user icon on top-right corner and login to your account
6. Remove yourself
7. Verify you not pro in https://zammad.eyecos.org/

# Servers
1. 5.75.148.51
2. 95.217.3.89

# Services
1. 5.75.148.51
  - postgres
  - minio
  - aexol-shop-backend: no repo
  - vendure-nextjs-storefront-main: no repo
  - node-webhook: no repo
2. 95.217.3.89
  - postgres
  - zammad-docker-compose: no repo
  - zammad-login: https://github.com/LuigiClemente/zammad-login
  - cube_zammad: https://github.com/LuigiClemente/cube_zammad.git
3. 5.161.233.158
  - camunda-platform: no repo

# Addition note
1. NEXT_PUBLIC_FAMILY_LIMIT in .env for family capacity
