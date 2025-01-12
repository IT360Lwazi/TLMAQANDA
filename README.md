# Recipes for AGP version `8.2.0`
This branch contains recipes compatible with AGP 8.2.0. If you want to find recipes
for other AGP versions, switch to the corresponding `agp-*` branch.

This branch is read only. Contributions are only accepted on the `studio-main` branch. See `CONTRIBUTION.md`
there.
# Recipes Index
Index is organized in categories, offering different ways to reach the recipe you want.
## Themes
* Android Assets - [addCustomAsset](addCustomAsset)
* Android Manifest - [createSingleArtifact](createSingleArtifact), [transformManifest](transformManifest), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Artifact API - [addMultipleArtifact](addMultipleArtifact), [transformAllClasses](transformAllClasses), [getMultipleArtifact](getMultipleArtifact), [workerEnabledTransformation](workerEnabledTransformation), [createSingleArtifact](createSingleArtifact), [getSingleArtifact](getSingleArtifact), [getScopedArtifacts](getScopedArtifacts), [appendToMultipleArtifact](appendToMultipleArtifact)
* DSL - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize), [extendingAgp](extendingAgp)
* Dependency Resolution - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Sources - [addCustomAsset](addCustomAsset), [addCustomSourceFolders](addCustomSourceFolders)
## APIs
* AndroidComponentsExtension.beforeVariants() - [selectVariants](selectVariants)
* AndroidComponentsExtension.onVariants() - [addCustomAsset](addCustomAsset), [addMultipleArtifact](addMultipleArtifact), [transformAllClasses](transformAllClasses), [getMultipleArtifact](getMultipleArtifact), [workerEnabledTransformation](workerEnabledTransformation), [createSingleArtifact](createSingleArtifact), [addCustomSourceFolders](addCustomSourceFolders), [allProjectsApkAction](allProjectsApkAction), [extendingAgp](extendingAgp), [addCustomBuildConfigFields](addCustomBuildConfigFields), [getSingleArtifact](getSingleArtifact), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [getScopedArtifacts](getScopedArtifacts), [transformManifest](transformManifest), [onVariants](onVariants), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [appendToMultipleArtifact](appendToMultipleArtifact)
* AndroidComponentsExtension.registerExtension() - [extendingAgp](extendingAgp)
* AndroidComponentsExtension.selector() - [allProjectsApkAction](allProjectsApkAction), [selectVariants](selectVariants)
* ApplicationVariant.applicationId - [onVariants](onVariants)
* ArtifactTransformationRequest - [workerEnabledTransformation](workerEnabledTransformation)
* Artifacts.add() - [addMultipleArtifact](addMultipleArtifact)
* Artifacts.forScope() - [transformAllClasses](transformAllClasses), [getScopedArtifacts](getScopedArtifacts)
* Artifacts.get() - [addCustomAsset](addCustomAsset), [addMultipleArtifact](addMultipleArtifact), [allProjectsApkAction](allProjectsApkAction), [getSingleArtifact](getSingleArtifact), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [appendToMultipleArtifact](appendToMultipleArtifact)
* Artifacts.getAll() - [getMultipleArtifact](getMultipleArtifact)
* Artifacts.use() - [workerEnabledTransformation](workerEnabledTransformation), [createSingleArtifact](createSingleArtifact), [transformManifest](transformManifest), [appendToMultipleArtifact](appendToMultipleArtifact)
* BuildConfigField() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* BuiltArtifact - [workerEnabledTransformation](workerEnabledTransformation)
* CanMinifyAndroidResourcesBuilder.shrinkResources - [selectVariants](selectVariants)
* CanMinifyCodeBuilder.isMinifyEnabled - [selectVariants](selectVariants)
* Component.artifacts - [addCustomAsset](addCustomAsset), [addMultipleArtifact](addMultipleArtifact), [getMultipleArtifact](getMultipleArtifact), [createSingleArtifact](createSingleArtifact), [getScopedArtifacts](getScopedArtifacts), [transformManifest](transformManifest), [appendToMultipleArtifact](appendToMultipleArtifact)
* Component.compileConfiguration - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Component.runtimeConfiguration - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Component.sources - [addCustomAsset](addCustomAsset), [addCustomSourceFolders](addCustomSourceFolders)
* Configuration.resolutionStrategy - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* DslExtension.Builder.build() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendBuildTypeWith() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendProductFlavorWith() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendProjectWith() - [extendingAgp](extendingAgp)
* DslLifecycle.finalizeDsl() - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* GeneratesApk.applicationId - [onVariants](onVariants)
* Gradle.beforeProject() - [allProjectsApkAction](allProjectsApkAction)
* HasUnitTestBuilder.enableUnitTest - [selectVariants](selectVariants)
* InAndOutDirectoryOperationRequest.toTransformMany() - [workerEnabledTransformation](workerEnabledTransformation)
* InAndOutFileOperationRequest.toTransform() - [transformManifest](transformManifest)
* MapProperty.put() - [addCustomBuildConfigFields](addCustomBuildConfigFields), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* MultipleArtifact.MULTIDEX_KEEP_PROGUARD - [getMultipleArtifact](getMultipleArtifact)
* MultipleArtifact.NATIVE_DEBUG_METADATA - [addMultipleArtifact](addMultipleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact)
* OutOperationRequest.toAppendTo() - [appendToMultipleArtifact](appendToMultipleArtifact)
* OutOperationRequest.toCreate() - [createSingleArtifact](createSingleArtifact)
* Plugin<Settings> - [allProjectsApkAction](allProjectsApkAction)
* ResolutionStrategy.dependencySubstitution() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* ScopedArtifact.CLASSES - [transformAllClasses](transformAllClasses), [getScopedArtifacts](getScopedArtifacts)
* ScopedArtifacts.Scope.ALL - [getScopedArtifacts](getScopedArtifacts)
* ScopedArtifacts.Scope.PROJECT - [transformAllClasses](transformAllClasses), [getScopedArtifacts](getScopedArtifacts)
* ScopedArtifacts.use() - [transformAllClasses](transformAllClasses), [getScopedArtifacts](getScopedArtifacts)
* ScopedArtifactsOperation.toGet() - [getScopedArtifacts](getScopedArtifacts)
* ScopedArtifactsOperation.toTransform() - [transformAllClasses](transformAllClasses)
* SingleArtifact.APK - [workerEnabledTransformation](workerEnabledTransformation), [allProjectsApkAction](allProjectsApkAction)
* SingleArtifact.ASSETS - [addCustomAsset](addCustomAsset)
* SingleArtifact.BUNDLE - [addMultipleArtifact](addMultipleArtifact), [getSingleArtifact](getSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact)
* SingleArtifact.MERGED_MANIFEST - [createSingleArtifact](createSingleArtifact), [transformManifest](transformManifest), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* SourceDirectories.addGeneratedSourceDirectory() - [addCustomAsset](addCustomAsset), [addCustomSourceFolders](addCustomSourceFolders)
* SourceDirectories.addStaticSourceDirectory() - [addCustomSourceFolders](addCustomSourceFolders)
* TaskBasedOperation.wiredWith() - [createSingleArtifact](createSingleArtifact)
* TaskBasedOperation.wiredWithDirectories() - [workerEnabledTransformation](workerEnabledTransformation)
* TaskBasedOperation.wiredWithFiles() - [transformManifest](transformManifest)
* TaskOutputs.upToDateWhen() - [transformManifest](transformManifest)
* TaskProvider.flatMap() - [createSingleArtifact](createSingleArtifact)
* TaskProvider.map() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* Variant.buildConfigFields - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* Variant.components - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Variant.manifestPlaceholders - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Variant.nestedComponents - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* VariantBuilder.minSdk - [selectVariants](selectVariants)
* VariantExtensionConfig - [extendingAgp](extendingAgp)
* VariantSelector.all() - [selectVariants](selectVariants)
* VariantSelector.withBuildType() - [allProjectsApkAction](allProjectsApkAction), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [selectVariants](selectVariants)
* VariantSelector.withFlavor() - [selectVariants](selectVariants)
* VariantSelector.withName() - [selectVariants](selectVariants)
* task.getOutputs() - [transformManifest](transformManifest)
## Call chains
* DslExtension.Builder().extendProjectWith().extendBuildTypeWith().extendProductFlavorWith().build() - [extendingAgp](extendingAgp)
* androidComponents.beforeVariants {} - [selectVariants](selectVariants)
* androidComponents.finalizeDsl {} - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* androidComponents.onVariants {} - [addCustomAsset](addCustomAsset), [addMultipleArtifact](addMultipleArtifact), [transformAllClasses](transformAllClasses), [getMultipleArtifact](getMultipleArtifact), [workerEnabledTransformation](workerEnabledTransformation), [createSingleArtifact](createSingleArtifact), [addCustomSourceFolders](addCustomSourceFolders), [allProjectsApkAction](allProjectsApkAction), [extendingAgp](extendingAgp), [addCustomBuildConfigFields](addCustomBuildConfigFields), [getSingleArtifact](getSingleArtifact), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [getScopedArtifacts](getScopedArtifacts), [transformManifest](transformManifest), [onVariants](onVariants), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [appendToMultipleArtifact](appendToMultipleArtifact)
* androidComponents.registerExtension() - [extendingAgp](extendingAgp)
* androidComponents.selector().all() - [selectVariants](selectVariants)
* androidComponents.selector().withBuildType() - [allProjectsApkAction](allProjectsApkAction), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [selectVariants](selectVariants)
* androidComponents.selector().withFlavor() - [selectVariants](selectVariants)
* androidComponents.selector().withName() - [selectVariants](selectVariants)
* configuration.resolutionStrategy.dependencySubstitution {} - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* settings.gradle.beforeProject {} - [allProjectsApkAction](allProjectsApkAction)
* substitute().using() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* task.outputs.upToDateWhen {} - [transformManifest](transformManifest)
* transformationRequest.submit() - [workerEnabledTransformation](workerEnabledTransformation)
* variant.applicationId - [onVariants](onVariants)
* variant.artifacts.add() - [addMultipleArtifact](addMultipleArtifact)
* variant.artifacts.forScope().use().toGet() - [getScopedArtifacts](getScopedArtifacts)
* variant.artifacts.forScope().use().toTransform() - [transformAllClasses](transformAllClasses)
* variant.artifacts.get() - [addCustomAsset](addCustomAsset), [addMultipleArtifact](addMultipleArtifact), [allProjectsApkAction](allProjectsApkAction), [getSingleArtifact](getSingleArtifact), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [appendToMultipleArtifact](appendToMultipleArtifact)
* variant.artifacts.getAll() - [getMultipleArtifact](getMultipleArtifact)
* variant.artifacts.use().wiredWith().toAppendTo() - [appendToMultipleArtifact](appendToMultipleArtifact)
* variant.artifacts.use().wiredWith().toCreate() - [createSingleArtifact](createSingleArtifact)
* variant.artifacts.use().wiredWithDirectories().toTransformMany() - [workerEnabledTransformation](workerEnabledTransformation)
* variant.artifacts.use().wiredWithFiles().toTransform() - [transformManifest](transformManifest)
* variant.buildConfigFields.put() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* variant.manifestPlaceholders.put() - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* variant.sources.*.addGeneratedSourceDirectory() - [addCustomAsset](addCustomAsset), [addCustomSourceFolders](addCustomSourceFolders)
* variant.sources.*.addStaticSourceDirectory() - [addCustomSourceFolders](addCustomSourceFolders)
## Others
* All projects - [allProjectsApkAction](allProjectsApkAction)
* Extending AGP DSL - [extendingAgp](extendingAgp)
* Placeholders - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* SourceDirectories.add - [addCustomSourceFolders](addCustomSourceFolders)
* registerSourceType - [addCustomSourceFolders](addCustomSourceFolders)
# License
```
Copyright 2022 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
