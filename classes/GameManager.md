The class is the GameManager, this class, well, manages the game and can be used to get certain variables and more.

Here are the known addresses:

```cpp
GameManager* Global_GameManager = base + 0x3222D0;

noreturn void __thiscall GameManager::~GameManager(GameManager* this) = base + 0xc49f0;

bool __thiscall GameManager::init(GameManager* this) = base + 0xc4ad0;

_ccColor3B* __thiscall GameManager::colorForIdx(GameManager* this, _ccColor3B* p0, int p1) = base + 0xc8d10;

void __thiscall GameManager::fadeInMusic(GameManager* this, char* p1) = base + 0xc4bd0;

bool __thiscall GameManager::getGameVariable(GameManager* this, char* p0) = base + 0xc9d30;

int __thiscall GameManager::getIntGameVariable(GameManager* this, char* key) = base + 0xca330;

GameManager* __thiscall getSharedState(GameManager* this) = base + 0xc4a50;

bool __thiscall GameManager::getUGV(GameManager* this, char* p1) = base + 0xca0d0;

void __thiscall GameManager::initSaveFile(GameManager* this, DS_Dictionary* p1) = base + 0xcdd20;

bool __thiscall GameManager::isColorUnlocked(GameManager* this, int id, bool type) = base + 0xc53f0;

bool __thiscall GameManager::isIconUnlocked(GameManager* this, int id, IconType type) = base + 0xc4fc0;

void __thiscall GameManager::loadBackground(GameManager* this, int p1) = base + 0xc9990;

void __thiscall GameManager::loadDeathEffect(GameManager* this, int p1) = base + 0xc9850;

void __thiscall GameManager::loadFont(GameManager* this, int p1) = base + 0xc9770;

void __thiscall GameManager::loadGround(GameManager* this, int p1) = base + 0xc9a50;

void __thiscall GameManager::logout(GameManager* this) = base + 0xcd3f0;

void __thicall GameManager::readSaveFile(GameManager* this, DS_Dictionary* p1) = base + 0xcc500;

void __thicall GameManager::reloadAll(GameManager* this, bool switchModes, bool toFullscreen) = base + 0xce950;

void __thiscall GameManager::reloadAllStep2(GameManager* this) = base + 0xce9e0;

void __thiscall GameManager::reportAchievementWithID(GameManager* this, char* p1, int p2, bool p3) = base + 0xc64c0;

void __thiscall GameManager::resolutionForKey(GameManager* this, CCSize* p1, uint p2) = base + 0xceca0;

void __thiscall GameManager::returnToLastScene(GameManager* this, GJGameLevel* level) = base + 0xce6a0;

void __thiscall GameManager::setGameVariable(GameManager* this, char* key, bool value) = base + 0xc9b50;

void __thiscall GameManager::setIntGameVariable(GameManager* this, char* key, int value) = base + 0xca230;

void __thiscall GameManager::setUGV(GameManager* this, char* key, bool value) = base + 0xc9f90;

void __thiscall GameManager::toggleGameVariable(GameManager* this, char* key) = base + 0xc9e90;

void __thiscall GameManager::update(GameManager* this, float p1) = base + 0xce440;

void __thiscall GameManager::backup(GameManager* this) = base + 0x28f60;

GameManager.PlayLayer = GameManager + 0x164

GameManager.EditorLayer = GameManager + 0x168

GameManager.userName = GameManager + 0x198
```
