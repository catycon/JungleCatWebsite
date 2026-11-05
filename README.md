== HERO MOVEMENT ==
HERO_WALK_SPEED = 0.65   (step 0.01)  walking / running speed on the ground
HERO_CROUCH_SPEED = 0.35   (step 0.01)  walking speed while crouching
HERO_SWIM_SPEED = 0.55   (step 0.01)  swimming speed in the water (sideways)
HERO_AIR_SPEED_FACTOR = 1.9   (step 0.1)  sideways speed in the air = walk speed x this (the hero flies further in a jump)
HERO_ROPE_SPEED = 0.75   (step 0.01)  speed while hanging on a rope hole
HERO_CLIMB_SPEED = 0.7   (step 0.01)  speed climbing up / down a vine
HERO_JUMP_SPEED = 2.975   (step 0.1)  start speed of a jump upwards
HERO_GRAVITY = 0.095   (step 0.001)  falling: speed gained every tick
HERO_MAX_FALL_SPEED = 4.5   (step 0.1)  falling never gets faster than this
HERO_CLIMB_JUMP_SPEED = 2.4   (step 0.1)  jump off a vine
HERO_CLIMB_TOP_HOP = 2   (step 1)  little hop when she climbs over the top of a vine
HERO_ROPE_HOP_UP = 1.6   (step 0.1)  hop up at the end of a rope hole
HERO_ROPE_HOP_SIDE = 0.65   (step 0.01)  hop sideways at the end of a rope hole
HERO_SPIKE_BOUNCE = 2.5   (step 0.1)  bounce up after she touched spikes
HERO_WATER_TICKS = 600   (step 10)  ticks in the deep water until she is eaten / drowns (600 = 10 seconds)
HERO_HURT_INVULN = 80   (step 5)  ticks she can not be hurt again after a hit
SWIM_SINK = 0.04   (step 0.001)  swimming: she sinks by this every tick
SWIM_DIVE = 0.1   (step 0.01)  swimming: extra downward push while the DOWN key is held
SWIM_RISE = 0.18   (step 0.01)  swimming: upward push while UP / JUMP is held
SWIM_MAX_UP = 1   (step 1)  swimming: fastest way up
SWIM_MAX_DOWN = 0.8   (step 0.01)  swimming: fastest way down
HOLE_POST_W = 10   (step 1)  
JUMP_SLOW = 0.704   (step 0.01)  
HERO_SLOW = 0.85   (step 0.01)  
VINE_G = 0.19   (step 0.01)  swing gravity of the swinging vines (was .38, faster).
VINE_LAUNCH = 1.41   (step 0.1)  swing gravity (was .38 = faster) and a launch boost so the jump distance stays the same
RUN_ANIM_K = 1.4   (step 0.1)  
HANG_K = 0.95   (step 0.01)  size of the vine-hang animation (1 = as exported)
JAPEX = 20   (step 1)  which picture (0-44) is shown at the top of the jump.
JRATE = 1.7   (step 0.1)  max pictures per tick (higher = snappier changes).
JLAND = 18   (step 1)  launch speed, apex frame (0-based), max frames per tick, ground distance where the landing reach starts
RESP_SAFE = 1   (step 1)  
RESP_BACK = 34   (step 5)  
RESP_MAX = 260   (step 10)  
RESP_HOLE = 60   (step 5)  
RESP_ENEMY = 110   (step 10)  
RESP_HIT = 1   (step 1)  
FADE_OUT = 70   (step 5)  
FADE_IN = 45   (step 5)  
SWK = 1.12   (step 0.1)  size of the swimming picture.
IK = 1.1   (step 0.1)  
HID_STEP = 110   (step 10)  hero idle: ticks one pose is held (the 6 new pictures play 1-2-3-4-5-6-5-4-3-2-1 ... and fade into each other).
HID_FADE = 0   (step 1)  part of every step used to fade into the next picture (0 = hard cut, 1 = always fading).
IW = 1.22   (step 0.1)  height / width factor of the idle pose.
DUCK_K = 0.9   (step 0.01)  duck pose size
CROUCH_ANIM = 1   (step 1)  1 = new crouch-down animation, 0 = old single picture.
CD_DN = 24   (step 5)  ticks to go down.
CD_UP = 16   (step 1)  ticks to stand up.
CD_DZ = 0.24   (step 0.01)  share of the time spent dissolving into the hold pose.
CLIMB_ON = 1   (step 1)  0 = old pose (run picture), 1 = the new climbing animation (33 pictures)
CLIMB_FPT = 0.5   (step 0.01)  pictures per game tick while she climbs (60 ticks/s -> 30 pictures/s). Up = forward,
CLIMB_K = 0.165   (step 0.01)  game units per picture pixel (size). CLIMB_AX / CLIMB_AY = point of the picture that sits on
CLIMB_AX = 147   (step 10)  
CLIMB_AY = 315   (step 10)  
CLIMB_DY = 2   (step 1)  
ROPE_ON = 1   (step 1)  0 = old pose (run picture + drawn arms), 1 = the hand-over-hand animation
ROPE_FPT = 0.7   (step 0.01)  
ROPE_K = 0.16   (step 0.01)  game units per picture pixel (size of the animation). ROPE_AX / ROPE_AY = the point of
ROPE_AX = 120   (step 10)  
ROPE_AY = 31   (step 5)  
ROPE_TILT = 0.5   (step 0.01)  
VL_ON = 1   (step 1)  0 = off (old behaviour).
VL_TPF = 1.7   (step 0.1)  game ticks per leap picture (19 pictures in about 32 ticks, the last one is held).
VL_HOLD = 10   (step 1)  
VL_AY = 25   (step 5)  

== HERO WEAPONS ==
WHIP_COOLDOWN = 26   (step 5)  ticks before the next whip hit
MACE_COOLDOWN = 18   (step 1)  ticks before the next mace hit
KNIFE_COOLDOWN = 20   (step 1)  ticks before the next knife throw
KNIFE_SPEED = 5   (step 1)  flying speed of a thrown knife (the hero's "bullet")
KNIFE_LIFE = 80   (step 5)  ticks a knife flies before it disappears
WH_T = 21   (step 5)  ticks of one whip swing (smaller = faster).
WH_A0 = -1.55   (step 0.1)  start angle.
WH_A1 = 0.5   (step 0.01)  end angle (guide arc for jumps / hanging).
WH_LAG = 0.38   (step 0.01)  how much the tip trails behind (the "crack").
WA_LAG = 2.5   (step 0.1)  same for the standing whip-attack pictures.
WP_N = 22   (step 5)  
WP_ST = 1.656   (step 0.1)  
WP_HD = 4   (step 1)  
WP_G = 0.085   (step 0.001)  
WP_DAMP = 0.985   (step 0.01)  
WP_BEND = 0.2   (step 0.01)  
WP_DRV = 0.26   (step 0.01)  
WP_FADE = 30   (step 5)  
WP_W1 = 1.3   (step 0.1)  
WP_W2 = 0.55   (step 0.01)  
WP_HX = 7   (step 1)  
WP_HY = -24   (step 5)  

== ENEMIES ==
SPEED_SNAKE = 0.25   (step 0.01)  
SPEED_BAT = 0.35   (step 0.01)  flying
SPEED_CROCODILE = 0.15   (step 0.01)  
SPEED_RAPTOR = 0.45   (step 0.01)  
SPEED_LIZARDMAN = 0.18   (step 0.01)  
SPEED_SPIDER = 0.3   (step 0.01)  
SPEED_DRAGONFLY = 0.5   (step 0.01)  flying
SPEED_BEAST = 0.14   (step 0.01)  
SPEED_SKELETON = 0.22   (step 0.01)  
BAT_BOB_PERIOD = 16   (step 1)  the bat flies up and down: bigger = slower
BAT_BOB_HEIGHT = 8   (step 1)  ... and this high (units)
DRAGONFLY_BOB_PERIOD = 9   (step 1)  
DRAGONFLY_BOB_HEIGHT = 12   (step 1)  
ENEMY_RESPAWN_TICKS = 18000   (step 50)  a killed enemy comes back after this many ticks (18000 = 5 minutes) - but only when you are more than 220 units away
NEVER_RESPAWN = 1000000000000   (step 50)  the gorilla and the woman boss use this: they never come back
ATK_ON = 1   (step 1)  1 = enemies play their attack animation, 0 = off.
ATK_T = 44   (step 5)  length of the attack animation in ticks.
ATK_CD = 150   (step 10)  ticks between two attack animations.
ATK_RY = 34   (step 5)  height tolerance for starting the attack.
SK_HIT = 1   (step 1)  1 = the long sword really hurts (in the last 2 attack pictures), 0 = it is only a picture.
SK_REACH = 44   (step 5)  
SPK_ON = 1   (step 1)  
SPK_K = 0.2   (step 0.01)  
SPK_HIT = 10   (step 1)  

== ARCHER 10 ==
ARR_VOL = 1   (step 1)  
ARC_ON = 1   (step 1)  
ARC_HP = 4   (step 1)  hits to kill her (machete, whip or throwing knives each count 1)
ARC_IDLE_LOOPS = 3   (step 1)  she plays her idle animation this many times, then does ONE attack (shoots one arrow), then idle again ... (replaces the old fixed time between arr...
ARC_IDLE_TPF = 4   (step 1)  ticks per idle picture (12 pictures: 4 -> one idle loop = 48 ticks = 0.8 s, 3 loops = 2.4 s)
ARC_FADE = 3   (step 1)  idle -> attack: the first attack pictures fade in over this many pictures (0 = hard cut)
ARC_TPF = 3.6   (step 0.1)  ticks per attack picture (25 pictures). Draw+shoot takes 25*3.6 = 90 ticks
ARC_REL = 22   (step 5)  picture at which the arrow leaves the bow (the game spawns the real arrow there)
ARC_RECOV = 16   (step 1)  
ARC_RANGE = 175   (step 10)  she starts shooting when you are closer than this many units
ARC_SPEED = 1.5   (step 0.1)  arrow speed (units/tick). ARC_AIM = .3 how steeply she may aim up/down
ARC_AIM = 0.3   (step 0.01)  
ARC_LEN = 21   (step 5)  drawn arrow length. ARC_K = .1548, ARC_AX/ARC_AY = size / feet anchor of her pictures
ARC_K = 0.1703   (step 0.01)  
ARC_AX = 156   (step 10)  
ARC_AY = 316   (step 10)  
ARC_SX = 13.5   (step 1)  
ARC_SY = 45.4   (step 1)  

== ARCHER 30 ==
ARC2_ON = 1   (step 1)  1 = she shoots, 0 = she only stands.
ARC2_HP = 2   (step 1)  hits to kill her.
ARC2_PERIOD = 300   (step 10)  ticks between two shots (5 s).
ARC2_RANGE = 175   (step 10)  she starts shooting closer than this.
ARC2_SPEED = 1.6   (step 0.1)  arrow speed.
ARC2_AIM = 0.8   (step 0.01)  how steeply she may aim up/down (was .3 = arrows went straight past you when you stood higher or lower).
ARC2_LEN = 24   (step 5)  arrow length (units).
ARC2_THICK = 1.7   (step 0.1)  arrow thickness (1 = as drawn).
ARC2_K = 0.129   (step 0.01)  size of the picture (bigger = taller girl).
ARC2_AX = 102   (step 10)  
ARC2_AY = 374   (step 10)  
ARC2_SX = 9   (step 1)  
ARC2_SY = 43   (step 5)  
ARC2_BX = 138   (step 10)  
ARC2_BY = 440   (step 10)  
ARC2_REC = 20   (step 1)  
ARC2_SCORE = 250   (step 10)  points for a kill.
ARC2_IT = 40   (step 5)  

== GORILLA ==
GOR_ON = 1   (step 1)  
GOR_HP = 6   (step 1)  hits to kill
GOR_REACH = 137.5   (step 10)  longest jump (units; was 125, now 10% wider)
GOR_JMIN = 3   (step 1)  
GOR_JMAX = 7   (step 1)  a visible gorilla hops 3 to 7 metres per jump (1 m = GOR_M units)
GOR_CATCH = 5   (step 1)  OFF screen he runs this many times faster and jumps GOR_REACH far, so he always catches up with you
GOR_STUCK = 90   (step 5)  off screen and no way forward (hole, wall) for this many ticks: he appears again on the ground behind you
GOR_ARC = 44.9   (step 1)  jump height (was 34, then 37.4, now +20% more)
GOR_UP = 26   (step 5)  highest step he can jump up
GOR_DROP = 90   (step 5)  deepest drop he jumps down
GOR_WATER = 205   (step 10)  ground lower than this is water
GOR_TPF = 6   (step 1)  ticks per attack picture (jump speed; was 2.4, then 3, now half the speed again)
GOR_F0 = 8   (step 1)  
GOR_FT = 17   (step 1)  
GOR_FL = 28   (step 5)  
GOR_REC = 68   (step 5)  
GOR_CD = 68   (step 5)  rest between jumps (ticks, was 34)
GOR_STOMP = 26   (step 5)  landing damage radius
GOR_K = 0.192   (step 0.01)  size (units per picture pixel)
GOR_AAX = 170   (step 10)  
GOR_AAY = 287.5   (step 10)  
GOR_IAX = 101.55   (step 10)  
GOR_IAY = 338.5   (step 10)  

== WOMAN BOSS ==
WBS_VOL = 1   (step 1)  
BOSS_FIRE_TICKS = 120   (step 10)  ticks between two shots (120 = one shot every 2 seconds). Higher = easier.
BOSS_BULLET_SPEED = 1.3   (step 0.1)  speed of the bullets (was 2.3). Lower = easier.
BOSS_WALK_TPF = 2.8   (step 0.1)  end boss walk: ticks per picture (bigger = slower legs)
WB_ON = 1   (step 1)  
WB_HP = 8   (step 1)  end boss hp:12 (+ hp0:12, in bossInit)
WB_PERIOD = 120   (step 10)  ticks between shots (120 = every 2 seconds)
WB_TPF = 5   (step 1)  ticks per attack picture (draw + aim + shoot = 50 ticks)
WB_RANGE = 230   (step 10)  she starts shooting when you are closer than this
WB_SPEED = 2.6   (step 0.1)  bullet speed
WB_AIM = 0.18   (step 0.01)  
WB_REL = 5   (step 1)  
WB_IT = 7   (step 1)  
WB_K = 0.1735   (step 0.01)  size WB_MX / WB_MY = muzzle position (35 / 40.6 units from her feet)
WB_AX = 259   (step 10)  
WB_AY = 308   (step 10)  
WB_MX = 35   (step 5)  
WB_MY = 40.6   (step 1)  

== SCREEN / MISC ==
DANCE_SECONDS = 5   (step 0.5)  seconds the win dance picture is shown before the win screen (space / enter / click skips it)
CHEAT_KEYS = 1   (step 1)  1 = test keys work while playing (5 = in front of an enemy 10 archer, 8 = enemy 30 archer, 7 = end boss, 6 = chimp, 0 = skeleton bridge, 9 = skip t...
CRAWL_K = 4.8   (step 0.1)  crawl animation speed: pictures per step of walking. Bigger = faster legs.
BR_ANCH = 0.76   (step 0.01)  share of the bridge picture above the walking line (bigger = bridge sits higher,
CL_ON = 1   (step 1)  
CL_ALPHA = 0.2   (step 0.01)  
CL_SPAN = 420   (step 10)  
CL_DRIFT = 0.03   (step 0.001)  
CL_Y = 34   (step 5)  height above the highest palm crown of the level (bigger = higher in the sky)

== CHIMP ==
CHAT_VOL = 0.8   (step 0.01)  
CHM_ON = 1   (step 1)  
CHM_HP = 2   (step 1)  hits to kill him
CHM_PERIOD = 300   (step 10)  ticks from one throw to the next (5 s)
CHM_RANGE = 150   (step 10)  he throws when you are closer than this (units)
CHM_TPF = 3.4   (step 0.1)  ticks per throw picture
CHM_ITPF = 2.4   (step 0.1)  ticks per idle picture
CHM_REL = 9   (step 1)  throw picture where the coconut leaves his hand
CHM_FLY = 1.7   (step 0.1)  coconut speed (units per tick), CHM_GRAV = .05 gravity
CHM_GRAV = 0.05   (step 0.001)  
CHM_K = 0.19   (step 0.01)  picture size (units per picture pixel)
CHM_BODY = 11.5   (step 1)  how far his body hangs beside the vine
CHM_LIFT = 26   (step 5)  height of his hit box above the ground
CHM_TOPY = 16.3   (step 1)  
CHM_ROPE = 130   (step 10)  rope length above him
CHM_W = 226   (step 10)  
CHM_H = 294   (step 10)  

== PRINCESS / DANCE ==
DANCE_SCALE = 1.2   (step 0.1)  size of the victory dance (1 = same height as the idle pose)
PIL_H = 70   (step 5)  
DANCE_ON = 1   (step 1)  1 = the dance plays after the boss, 0 = no dance.
DANCE_TPF = 2.5   (step 0.1)  ticks per picture (2.5 = the video's 24 pictures per second).
DANCE_LOOPS = 3   (step 1)  how many times the dance is played.
PR_ON = 1   (step 1)  
PR_K = 0.1985   (step 0.01)  size (units per picture pixel; the hero's dance is about .2)
PR_X = 18041   (step 50)  
PR_FY = 129.5   (step 10)  where she stands (centre x / feet y)
PR_DX = 42   (step 5)  distance between the two dancers
CAP_ON = 1   (step 1)  
CAP_X = 17862   (step 50)  
CAP_FY = 176   (step 10)  
CAP_K = 0.165   (step 0.01)  
CAP_TPF = 6   (step 1)  
CAP_ALPHA = 1   (step 1)  
CAP_VOL = 1   (step 1)  volume of the scene's sound (audio/captive_scene.mp3), played once at the start of every loop of the animation. 0 = silent
PRH_ON = 1   (step 1)  
PRH_X = 18028.6   (step 1000)  
PRH_FY = 131.9   (step 10)  
PRH_K = 0.13196   (step 0.01)  

== RED GEMS ==
RED_GEMS_ON = 1   (step 1)  
RED_GEM_DAMAGE = 1   (step 1)  hearts lost when she touches a red gem
RED_GEM_HIT = 6   (step 1)  half size of the dangerous part (units) around the gem centre

== ANIMATION FRAMES ==
FRAMES_SNAKE_MOVE = 4   (step 1)  number of pictures of the animation "snake move" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_SNAKE_ATTACK = 4   (step 1)  number of pictures of the animation "snake attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_BAT_FLY = 4   (step 1)  number of pictures of the animation "bat fly" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_BAT_ATTACK = 4   (step 1)  number of pictures of the animation "bat attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_CROCODILE_SWIM = 4   (step 1)  number of pictures of the animation "crocodile swim" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_CROCODILE_ATTACK = 4   (step 1)  number of pictures of the animation "crocodile attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_RAPTOR_RUN = 4   (step 1)  number of pictures of the animation "raptor run" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_RAPTOR_ATTACK = 4   (step 1)  number of pictures of the animation "raptor attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_LIZARDMAN_WALK = 4   (step 1)  number of pictures of the animation "lizardman walk" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_LIZARDMAN_ATTACK = 4   (step 1)  number of pictures of the animation "lizardman attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_SPIDER_WALK = 4   (step 1)  number of pictures of the animation "spider walk" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_SPIDER_ATTACK = 4   (step 1)  number of pictures of the animation "spider attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_DRAGONFLY_FLY = 4   (step 1)  number of pictures of the animation "dragonfly fly" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_DRAGONFLY_ATTACK = 4   (step 1)  number of pictures of the animation "dragonfly attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_BEAST_WALK = 4   (step 1)  number of pictures of the animation "beast walk" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_BEAST_ATTACK = 4   (step 1)  number of pictures of the animation "beast attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_SKELETON_WALK = 36   (step 1)  number of pictures of the animation "skeleton walk" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_SKELETON_ATTACK = 4   (step 1)  number of pictures of the animation "skeleton attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_BOSS_WALK = 81   (step 1)  number of pictures of the animation "end boss walk" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_CAPTIVE = 17   (step 1)  number of pictures of the animation "captive" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_ARCHER10_IDLE = 12   (step 1)  number of pictures of the animation "archer10 idle" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_ARCHER10_ATTACK = 25   (step 1)  number of pictures of the animation "archer10 attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_ARCHER30_IDLE = 17   (step 1)  number of pictures of the animation "archer30 idle" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_ARCHER30_ATTACK = 39   (step 1)  number of pictures of the animation "archer30 attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_GORILLA_ATTACK = 30   (step 1)  number of pictures of the animation "gorilla attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_GORILLA_IDLE = 2   (step 1)  number of pictures of the animation "gorilla idle" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_WOMANBOSS_ATTACK = 6   (step 1)  number of pictures of the animation "womanboss attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_WOMANBOSS_IDLE = 7   (step 1)  number of pictures of the animation "womanboss idle" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_CHIMP_HANG = 48   (step 1)  number of pictures of the animation "chimp hang" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_CHIMP_THROW = 12   (step 1)  number of pictures of the animation "chimp throw" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_SWIM = 11   (step 1)  number of pictures of the animation "hero swim" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_HANG = 21   (step 1)  number of pictures of the animation "hero hang" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_JUMP = 45   (step 1)  number of pictures of the animation "hero jump" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_WHIP_ATTACK = 11   (step 1)  number of pictures of the animation "hero whip attack" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_CROUCH_DOWN = 5   (step 1)  number of pictures of the animation "hero crouch down" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_CLIMB = 33   (step 1)  number of pictures of the animation "hero climb" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_SWING_LEAP = 19   (step 1)  number of pictures of the animation "hero swing leap" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_CLOUDS = 5   (step 1)  number of pictures of the animation "clouds" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_PRINCESS_DANCE = 82   (step 1)  number of pictures of the animation "princess dance" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_IDLE = 6   (step 1)  number of pictures of the animation "hero idle" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_ROPE_HANG = 37   (step 1)  number of pictures of the animation "hero rope hang" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_CRAWL = 45   (step 1)  number of pictures of the animation "hero crawl" (the numbered files in the graphics folder). Needs a page reload (F5).
FRAMES_HERO_DANCE = 90   (step 1)  number of pictures of the animation "hero dance" (the numbered files in the graphics folder). Needs a page reload (F5).
