This class allows you to show an achievement message.

Showing the achievement should be called from the main thread (like from a button press, etc.)

Here are the known addresses:

```cpp
noreturn void __thiscall AchievementBar::~AchievementBar(AchievementBar* this, byte p1) = base + 0x3b0e0;

AchievementBar* __thiscall AchievementBar::create(AchievementBar* this, char* title, char* desc, char* icon, bool quest) = base + 0x3b120;

AchievementBar* __fastcall AchievementBar::getSharedState() = base + 0xfc90;

void __fastcall AchievementBar::show(CCNode* p1) = base + 0x3BE50;

void __thiscall AchievementBar::showNextAchievement(AchievementBar* this, int p1) = base + 0xFD60;

void __thiscall AchievementBar::unk1(AchievementBar* this, undefined4 p1) = base + 0x3c090;
```
