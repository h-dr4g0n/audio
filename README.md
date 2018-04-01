# audio
var e = GC.app.mvc.models.RaidsModel;
GC.app.mvc.sendNotification("SaveBossRaidDamageCommand", {
    bossRaidDamage: 9999999999,
    raidData: e
})
