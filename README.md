# yii2-library
配置示例，主要添加一个 repository https://github.com/limefamily/yii2-library.git

    {
        "name": "yiisoft/yii2-app-advanced",
        "description": "Yii 2 Advanced Project Template",
        "keywords": ["yii2", "framework", "advanced", "project template"],
        "homepage": "http://www.yiiframework.com/",
        "type": "project",
        "license": "BSD-3-Clause",
        "support": {
            "issues": "https://github.com/yiisoft/yii2/issues?state=open",
            "forum": "http://www.yiiframework.com/forum/",
            "wiki": "http://www.yiiframework.com/wiki/",
            "irc": "irc://irc.freenode.net/yii",
            "source": "https://github.com/yiisoft/yii2"
        },
        "minimum-stability": "stable",
        "require": {
            "php": ">=5.4.0",
            "yiisoft/yii2": "~2.0.6",
            "yiisoft/yii2-bootstrap": "~2.0.0",
            "yiisoft/yii2-swiftmailer": "~2.0.0 || ~2.1.0",
            "yiisoft/yii2-httpclient": "^2.0",
            "aws/aws-sdk-php": "^3.52",
            "limefamily/yii2-library": "dev-master"
        },
        "require-dev": {
            "yiisoft/yii2-debug": "~2.0.0",
            "yiisoft/yii2-gii": "~2.0.0",
            "yiisoft/yii2-faker": "~2.0.0",
            "codeception/base": "^2.2.3",
            "codeception/verify": "~0.3.1"
        },
        "config": {
            "process-timeout": 1800
        },
        "repositories": [
            {
                "type": "composer",
                "url": "https://packagist.phpcomposer.com"
            },{
                "type": "vcs",
                "url": "https://github.com/limefamily/yii2-library.git"
            }
        ]
    }

composer require limefamily/yii2-library:dev-master
