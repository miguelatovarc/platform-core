# Authentication Flow

## Login
1. POST /auth/login {email, password}
2. Validate credentials
3. Generate JWT (15min) + Refresh Token (7d)
4. Return tokens

## Refresh
1. POST /auth/refresh {refresh_token}
2. Validate + rotate refresh token
3. Return new pair
