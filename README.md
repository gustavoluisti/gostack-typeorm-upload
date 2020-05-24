yarn typeorm migration:create -n CreateTransactions
yarn typeorm migration:create -n CreateCategories
yarn typeorm migration:create -n AddCategoryToTransactions
yarn typeorm migration:run
yarn typeorm migration:revert
