# fizzbuzz-api


# Test
```bash
python -m pytest
```

# Deploy
```bash
zip lambda lambda_function.py test_lambda_function.py README.md
aws lambda update-function-code --function-name FizzBuzz-Calculator-Mandzik --zip-file fileb://lambda.zip
```