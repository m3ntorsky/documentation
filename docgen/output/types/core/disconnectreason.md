---
title: DisconnectReason
index: true
order: 2
category:
  - Guide
---

# DisconnectReason
::: tabs
@tab Lua
```lua
DisconnectReason = {
    Invalid = 0,
    Shutdown = 1,
    DisconnectByUser = 2,
    DisconnectByServer = 3,
    Lost = 4,
    Overflow = 5,
    SteamBanned = 6,
    SteamInUse = 7,
    SteamTicket = 8,
    SteamLogon = 9,
    SteamAuthCancelled = 10,
    SteamAuthAlreadyUsed = 11,
    SteamAuthInvalid = 12,
    SteamVacBanned = 13,
    SteamLoggedInElsewhere = 14,
    SteamVacCheckTimedout = 15,
    SteamDropped = 16,
    SteamOwnership = 17,
    ServerInfoOverflow = 18,
    TickMsgOverflow = 19,
    StringTableMsgOverflow = 20,
    DeltaentMsgOverflow = 21,
    TempentMsgOverflow = 22,
    SoundsMsgOverflow = 23,
    SnapshotOverflow = 24,
    SnapshotError = 25,
    ReliableOverflow = 26,
    BadDeltaTick = 27,
    NoMoreSplits = 28,
    Timedout = 29,
    Disconnected = 30,
    LeavingSplit = 31,
    DifferentClassTables = 32,
    BadRelayPassword = 33,
    BadSpectatorPassword = 34,
    HLTVRestricted = 35,
    NoSpectators = 36,
    HLTVUnavailable = 37,
    HLTVStop = 38,
    Kicked = 39,
    BanAdded = 40,
    KickBanAdded = 41,
    HLTVDirect = 42,
    PureServerClientExtra = 43,
    PureServerMismatch = 44,
    UserCmd = 45,
    RejectedByGame = 46,
    MessageParseError = 47,
    InvalidMessageError = 48,
    BadServerPassword = 49,
    DirectConnectReservation = 50,
    ConnectionFailure = 51,
    NoPeerGroupHandlers = 52,
    Reconnection = 53,
    LoopShutdown = 54,
    LoopDeactivate = 55,
    HostEndGame = 56,
    LoopLevelLoadActivate = 57,
    CreateServerFailed = 58,
    Exiting = 59,
    RequestHostStateIdle = 60,
    RequestHostStateHLTVRelay = 61,
    ClientConsistencyFail = 62,
    UnableToCRCMap = 63,
    ClientNoMap = 64,
    ClientDifferentMap = 65,
    ServerRequiresSteam = 66,
    SteamDenyMisc = 67,
    SteamDenyBadAnticheat = 68,
    ServerShutdown = 69
}
```
:::