# DB Rules

BAD:
"SELECT * FROM users WHERE name = '" + input + "'"

GOOD:
PreparedStatement
