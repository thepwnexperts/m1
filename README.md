# m1

## About server-client side validation vectors
Attacker can hack/compromise users data using unsecure backend and frontend combination.

# Backend

1. sm1 (price tempering)
    - https://github.com/thepwnexperts/m1-sm1-b1 [have secure but if use /cal endpoint]

`sm2 and sm3 related to response manipulation`

2. sm2 (otp validation)

    - https://github.com/thepwnexperts/m1-sm2-b1 [unsecure validation at client side]

    - https://github.com/thepwnexperts/m1-sm2-b2 [secure]

3. sm3 (secure fetching ->this may consider as secure data exchange) 
    - https://github.com/thepwnexperts/m1-sm3-b1 [secure depends on fetching method] 

# Frontend

1. sm1 (price tempering)
    - https://github.com/thepwnexperts/m1-sm1-u1 [unsecure]

    - https://github.com/thepwnexperts/m1-sm1-u2 [secure]

2. sm2 (otp validation)

    - https://github.com/thepwnexperts/m1-sm2-u1 [secure]

    - https://github.com/thepwnexperts/m1-sm2-u2 [unsecure]

3. sm3 (secure fetching)

    - https://github.com/thepwnexperts/m1-sm3-u1

    - https://github.com/thepwnexperts/m1-sm3-u2

