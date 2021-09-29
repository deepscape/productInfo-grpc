
# ghz stress tool script 
brew install ghz

ghz --insecure --proto /Users/hdkim/Documents/workMain/ideaProjects/productInfo-grpc/productInfo-grpc-server/src/main/proto/product_info.proto -n 10 -c 2 \
--call ecommerce.ProductInfo/getProduct \
--format=summary \
-d '[{"value":"1"}, {"value":"2"}, {"value":"3"}, {"value":"4"}, {"value":"5"}]' \
localhost:50051     



# Gradle 6.9.1 필요

Gradle 7.0 이상에서 비정상 동작 

Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/6.9.1/userguide/command_line_interface.html#sec:command_line_warnings

> Entry META-INF/INDEX.LIST is a duplicate but no duplicate handling strategy has been set.

