trigger MyTriggerName on ObjectName (before insert, before update) {
    if (Trigger.isBefore) {
        if (Trigger.isInsert) {
            // Code to run before records are inserted
        }
        if (Trigger.isUpdate) {
            // Code to run before records are updated
        }
    }
}
