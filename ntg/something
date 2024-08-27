
resource "azapi_resource" "symbolicname" {
  type = "Microsoft.Sql/servers/databases@2023-05-01-preview"
  name = "string"
  location = "string"
  parent_id = "string"
  tags = {
    tagName1 = "tagValue1"
    tagName2 = "tagValue2"
  }
  identity {
    type =  "UserAssigned"
    identity_ids = []
  }
  body = jsonencode({
    properties = {
      autoPauseDelay = int
      availabilityZone = "string"
      catalogCollation = "string"
      collation = "string"
      createMode = "string"
      elasticPoolId = "string"
      encryptionProtector = "string"
      encryptionProtectorAutoRotation = bool
      federatedClientId = "string"
      freeLimitExhaustionBehavior = "string"
      highAvailabilityReplicaCount = int
      isLedgerOn = bool
      keys = {
        {customized property} = {}
      }
      licenseType = "string"
      longTermRetentionBackupResourceId = "string"
      maintenanceConfigurationId = "string"
      manualCutover = bool
      maxSizeBytes = int
      minCapacity = "decimal-as-string"
      performCutover = bool
      preferredEnclaveType = "string"
      readScale = "string"
      recoverableDatabaseId = "string"
      recoveryServicesRecoveryPointId = "string"
      requestedBackupStorageRedundancy = "string"
      restorableDroppedDatabaseId = "string"
      restorePointInTime = "string"
      sampleName = "string"
      secondaryType = "string"
      sourceDatabaseDeletionDate = "string"
      sourceDatabaseId = "string"
      sourceResourceId = "string"
      useFreeLimit = bool
      zoneRedundant = bool
    }
    sku = {
      capacity = int
      family = "string"
      name = "string"
      size = "string"
      tier = "string"
    }
  })
}
