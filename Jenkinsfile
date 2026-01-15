@Library('Jenkins-shared-library') _

mlModelPipeline(
    appName: 'predictive-heatmaps-of-neighborhood-price-evolution',
    hfRepo: 'saaymo/Predictive-heatmaps-of-neighborhood-price-evolution',
    modelFiles: [
        [name: 'k_means_model.pkl', targetDir: 'model/models'],
        [name: 'preprocessor.pkl', targetDir: 'model/models'],
        [name: 'property_feature_matrix.npy', targetDir: 'model/data']
    ]
)
