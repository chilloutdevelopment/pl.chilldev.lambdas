<!---
# This file is part of the pl.wrzasq.lambda.
#
# @license http://mit-license.org/ The MIT license
# @copyright 2018 - 2019 © by Rafał Wrzeszcz - Wrzasq.pl.
-->

# WrzasqPl-Lambda

**WrzasqPl-Lambda** is a set of generic **AWS Lambda**s.

[![Build Status](https://travis-ci.com/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda.svg)](https://travis-ci.com/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda)
[![Coverage Status](https://coveralls.io/repos/github/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda/badge.svg?branch=develop)](https://coveralls.io/github/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda?branch=develop)
[![Known Vulnerabilities](https://snyk.io/test/github/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda/badge.svg)](https://snyk.io/test/github/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda)

# Usage

Each **Lambda** module is a stand-alone, independent package. Ready to be deployed into **AWS** out of the box.

Keep in mind, that you can use **Lambda** packages regardless of your technology - they are completely independent,
running in [_FaaS_](https://en.wikipedia.org/wiki/Function_as_a_service) environment, communicating through
**JSON**-based interface.

You can use virtually any tool and integrate them with any project. No piece of your code will directly interact with
this source code.

# Lambdas

## [Lambda@Edge deploy](https://rafalwrzeszcz-wrzasqpl.github.io/pl.wrzasq.lambda/lambda-edgedeploy/)

This is a [**CloudFormation**](https://aws.amazon.com/cloudformation/) custom resource handler (implemented using
[`pl.wrzasq.commons:commons-aws`](https://rafalwrzeszcz-wrzasqpl.github.io/pl.wrzasq.commons/commons-aws/)). It allows
to deploy [**Lambda@Edge**](https://aws.amazon.com/lambda/edge/) functions from any region and expose their to
[`AWS::CloudFront::Distribution`](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-cloudfront-distribution.html)
resource.

## [Lambda-CForm Organization](https://rafalwrzeszcz-wrzasqpl.github.io/pl.wrzasq.lambda/lambda-cform/lambda-organization/)

**CloudFormation** custom resource handlers for organization management.

# Resources

-   [GitHub page with API documentation](https://rafalwrzeszcz-wrzasqpl.github.io/pl.wrzasq.lambda)
-   [Contribution guide](https://github.com/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda/blob/develop/CONTRIBUTING.md)
-   [Issues tracker](https://github.com/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda/issues)
-   [Maven packages](https://search.maven.org/search?q=g:pl.wrzasq.lambda)
-   [Wrzasq.pl @ GitHub](https://github.com/rafalwrzeszcz-wrzasqpl)
-   [Wrzasq.pl @ Facebook](https://www.facebook.com/wrzasqpl)
-   [Post on Wrzasq.pl](http://wrzasq.pl/blog/deploying-lambda-edge-with-pl-chilldev-lambda.html)

# Authors

This project is published under [MIT license](https://github.com/rafalwrzeszcz-wrzasqpl/pl.wrzasq.lambda/tree/master/LICENSE).

**pl.wrzasq.lambda** is brought to you by [Rafał Wrzeszcz - Wrzasq.pl](https://wrzasq.pl).

List of contributors:

-   [Rafał "Wrzasq" Wrzeszcz](https://github.com/rafalwrzeszcz) ([wrzasq.pl](https://wrzasq.pl)).