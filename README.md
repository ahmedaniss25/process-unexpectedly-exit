
configurations.matching { it.name == '_internal_aapt2_binary' }.all { config ->
        config.resolutionStrategy.eachDependency { details ->
            details.useVersion("3.3.2-5309881")
        }
    }


