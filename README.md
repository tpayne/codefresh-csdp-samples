# codefresh-csdp-samples
Codefresh CSDP samples

cf git-source create pipeline-dev applications \
    --git-src-repo https://github.com/tpayne/codefresh-csdp-samples.git/argocd/dev \
    --git-token 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

cf git-source create pipeline-qa applications \
    --git-src-repo https://github.com/tpayne/codefresh-csdp-samples.git/argocd/qa \
    --git-token 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

cf git-source create pipeline-sit applications \
    --git-src-repo https://github.com/tpayne/codefresh-csdp-samples.git/argocd/sit \
    --git-token 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

cf git-source create pipeline-preprod applications \
    --git-src-repo https://github.com/tpayne/codefresh-csdp-samples.git/argocd/preprod \
    --git-token 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

cf git-source create pipeline-prod applications \
    --git-src-repo https://github.com/tpayne/codefresh-csdp-samples.git/argocd/prod \
    --git-token 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