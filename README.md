# estudo-serverless-framework-framework

## tutorial-serverless-node-offline

## python example
```bash
# instala o serverless globalmente
npm install -g serverless

# executa a lambda
serverless invoke local -f hello

# executa a lambda passando objeto como event para lambda
serverless invoke local -f hello --data '{"a":"bar"}'

# executa a lambda passando objeto e uma variável
serverless invoke local -f hello \
--data '{"a":"bar"}' \
-e VAR1='algum valor'
```

## Links
- [Como construir uma API poderosa com Node.js, Serverless e Lambda](https://how.kovi.work/construindo-uma-aplica%C3%A7%C3%A3o-serverless-do-zero-cd0d70527d61)
- [Local development with Serverless](https://towardsaws.com/local-development-with-serverless-46a219876a67)
- [serverless invoke local](https://www.serverless.com/framework/docs/providers/aws/cli-reference/invoke-local)
- [Usando LocalStack junto com Serverless Framework: Um guia passo a passo](https://www.linkedin.com/pulse/usando-localstack-junto-com-serverless-framework-um-guia-felipe/?originalSubdomain=pt)
