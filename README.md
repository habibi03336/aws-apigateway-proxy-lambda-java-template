# aws-apigateway-proxy-labmda-java-template

This is a template for aws lambda function using java programming language that handles api gateway request proxy.

## description 
### feat
func1, func2 are sample of feats. You can program how to handle requests and how to response. One feat is one aws lambda.

### common
Probably, some features would be shared between feats such as domains and repositories. Shared data types and features can be defined here and shared.

### settings.gradle
By this file, you can specify which feat to build. Build results would be placed inside each feat.

## how to deploy on lambda
jar file contains all things needed including commons and dependencies(a.k.a 'fat jar'). Therefore you can just deploy "build/libs/{feat-name}-all.jar" on your lambda and hope it works.
