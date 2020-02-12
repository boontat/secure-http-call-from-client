# Secure HTTP Call From Client
Research on ways or technique to use for secure http call from client side

# How I Think It Is Secure
1. Third party API calls should always be wrapped within the application. Third party API call should not be directly call from client side.
2. In the application that actually execute the third party API should at list check the whitelisted caller remote address.
