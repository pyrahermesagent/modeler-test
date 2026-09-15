# Verification Report

- Repo: `output/Carcassonne/.repo` (pinned tree for citations)
- Generated: 2026-09-14T22:26:19+00:00

## Specification.md

**Status: PASS** - citations 231/231 ok; mermaid blocks: 1 (flowchart)

### Resolved citations (verify by eye against the code)
| Doc line | Citation | Context at cited line |
| --: | :-- | :-- |
| 9 | `src/Types/Game.elm:43-45` | - |
| 9 | `src/Backend.elm:105-110` | else |
| 9 | `src/Views/PlayerLobbyView.elm:20-37` | , renderPlayerNames players |
| 13 | `src/Frontend.elm:50-62` | - |
| 13 | `src/Backend.elm:93-118` | case ( msg, model ) of |
| 13 | `src/Backend.elm:125-138` | - |
| 13 | `src/Backend.elm:120-123` | - |
| 14 | `src/Types/Game.elm:120-147` | -} |
| 14 | `src/Helpers/GameLogic.elm:323-370` | -} |
| 14 | `src/Helpers/GameLogic.elm:21-40` | -} |
| 14 | `src/Helpers/GameLogic.elm:383-508` | -} |
| 14 | `src/Helpers/GameLogic.elm:511-556` | - |
| 15 | `src/Views/GameView.elm:743-745` | [ text "Rotate Tile" ] |
| 15 | `src/Backend.elm:180-183` | - |
| 16 | `.github/workflows/test.yaml:33-46` | - |
| 18 | `readme.md:61` | 1) Draw 1 tile and place it on the board. If it can not be placed, shuffle it back and draw a new on |
| 18 | `readme.md:79` | - Incomplete Cloister is worth 1 for adjacent tile + 1 point for itself. |
| 19 | `readme.md:50-52` | - |
| 19 | `src/Types/Game.elm:61` | { playerScores = Dict.fromList (List.map (\playerName -> ( playerName, 0 )) players) |
| 20 | `readme.md:117` | - PlaceMeeple - Player may place a meeple on the tile played |
| 22 | `readme.md:81-85` | - |
| 25 | `src/Helpers/GameLogic.elm:311-314` | - |
| 25 | `src/Helpers/GameLogic.elm:373-376` | - |
| 26 | `src/Backend.elm:14-15` | - |
| 27 | `src/Evergreen/Migrate/V10.elm:3` | - |
| 30 | `src/Frontend.elm:17-31` | - |
| 30 | `src/Backend.elm:18-25` | - |
| 30 | `src/Backend.elm:6` | import Helpers.TileMapper exposing (getTile) |
| 30 | `src/Evergreen/Migrate/V10.elm:3-18` | - |
| 36 | `src/Views/PlayerRegistrationView.elm:1` | module Views.PlayerRegistrationView exposing (..) |
| 37 | `src/Views/PlayerLobbyView.elm:1` | module Views.PlayerLobbyView exposing (..) |
| 38 | `src/Views/GameView.elm:1` | module Views.GameView exposing (..) |
| 39 | `src/Helpers/FrontendHelpers.elm:48-110` | -} |
| 44 | `src/Types.elm:50-58` | - |
| 50 | `src/Helpers/GameLogic.elm:1` | module Helpers.GameLogic exposing (..) |
| 51 | `src/Helpers/TileMapper.elm:9-253` | -} |
| 54 | `src/Types.elm:11-17` | - |
| 66 | `src/Views/PlayerRegistrationView.elm:16-37` | [ Html.form |
| 78 | `elm.json:6` | ], |
| 78 | `elm.json:9` | "direct": { |
| 78 | `elm.json:12` | "elm/core": "1.0.5", |
| 78 | `src/Styles.elm:1` | module Styles exposing (..) |
| 79 | `elm.json:17-18` | "elm-explorations/test": "2.2.0", |
| 79 | `src/Backend.elm:147` | ( BeGamePlayed { game = game } |
| 79 | `src/Backend.elm:177` | ( BeGamePlayed { game = updatedGame } |
| 82 | `readme.md:139-151` | - |
| 82 | `elm.json:16` | "elm-community/random-extra": "3.2.0", |
| 82 | `.github/workflows/test.yaml:36-37` | - |
| 84 | `src/Backend.elm:95-101` | let |
| 84 | `src/Types/PlayerName.elm:4-5` | - |
| 84 | `src/Views/PlayerRegistrationView.elm:29-37` | ] |
| 84 | `src/Backend.elm:125-133` | - |
| 84 | `src/Backend.elm:140-148` | - |
| 89 | `src/Views/PlayerRegistrationView.elm:16-26` | [ Html.form |
| 90 | `src/Frontend.elm:98-124` | - |
| 90 | `src/Views/PlayerLobbyView.elm:30-37` | ul Styles.playerList |
| 91 | `src/Types/Game.elm:53-73` | -} |
| 91 | `src/Backend.elm:44-59` | - |
| 91 | `src/Views/PlayerLobbyView.elm:20-23` | , renderPlayerNames players |
| 92 | `src/Views/GameView.elm:327` | , style "cursor" "pointer" |
| 93 | `src/Views/GameView.elm:740-742` | , br [] [] |
| 93 | `src/Helpers/GameLogic.elm:45-95` | -} |
| 94 | `src/Helpers/FrontendHelpers.elm:27-43` | -} |
| 95 | `src/Helpers/GameLogic.elm:256-290` | -} |
| 95 | `src/Helpers/GameLogic.elm:170-203` | -} |
| 95 | `src/Helpers/GameLogic.elm:430-436` | in |
| 96 | `src/Frontend.elm:125-132` | - |
| 96 | `readme.md:121-123` | - |
| 100 | `src/Backend.elm:185-186` | - |
| 101 | `src/Types.elm:20-33` | - |
| 102 | `src/Types/GameState.elm:4-7` | - |
| 102 | `src/Helpers/GameLogic.elm:367` | , nextSideId = getTileMaximumSideId tileToPlace |
| 102 | `src/Helpers/GameLogic.elm:502-508` | in |
| 102 | `src/Helpers/GameLogic.elm:552-556` | in |
| 104 | `src/Backend.elm:189-191` | - |
| 105 | `.github/workflows/test.yaml:45-46` | - |
| 109 | `src/Backend.elm:37-38` | - |
| 111 | `src/Backend.elm:40-42` | case ( msg, model ) of |
| 112 | `src/Evergreen/Migrate/V10.elm:36-43` | - |
| 112 | `src/Frontend.elm:28` | } |
| 118 | `src/Types/Game.elm:28-40` | - |
| 118 | `src/Types/Game.elm:20-21` | - |
| 118 | `src/Types/Game.elm:16-17` | - |
| 118 | `src/Types/Game.elm:24-25` | - |
| 119 | `src/Types/Tile.elm:21-29` | - |
| 119 | `src/Types/Tile.elm:15-18` | - |
| 119 | `src/Types/Meeple.elm:17-23` | - |
| 119 | `src/Types/Feature.elm:4-8` | - |
| 119 | `src/Types/Coordinate.elm:4-5` | - |
| 119 | `src/Types/PlayerIndex.elm:4-5` | - |
| 119 | `src/Types/Score.elm:4-5` | - |
| 120 | `src/Types/Game.elm:102-104` | -} |
| 120 | `src/Types/Meeple.elm:26-42` | - |
| 121 | `src/Evergreen/Migrate/V3.elm:27-54` | - |
| 121 | `src/Evergreen/Migrate/V5.elm:120-156` | - |
| 121 | `src/Evergreen/Migrate/V10.elm:36-63` | - |
| 122 | `src/Frontend.elm:143-150` | - |
| 122 | `src/Backend.elm:167` | ( BeGamePlayed { game = updatedGame } |
| 122 | `src/Types/Tile.elm:28` | , west : Side |
| 122 | `src/Types.elm:23` | { nameInput : String |
| 126 | `src/Types.elm:50-86` | - |
| 131 | `src/Types.elm:51` | type ToBackend |
| 132 | `src/Types.elm:52` | = RegisterPlayer PlayerName |
| 133 | `src/Types.elm:53` | | KickPlayer PlayerName |
| 134 | `src/Types.elm:54` | | KillLobby |
| 135 | `src/Types.elm:55` | | InitializeGame |
| 136 | `src/Types.elm:56` | | RotateTileLeft |
| 137 | `src/Types.elm:57` | | PlaceTile Coordinate |
| 138 | `src/Types.elm:58` | | PlaceMeeple MeeplePosition |
| 139 | `src/Types.elm:62` | type BackendMsg |
| 140 | `src/Types.elm:63` | = ClientConnected SessionId ClientId |
| 141 | `src/Types.elm:64` | | InitializeGameAndTileDrawStackShuffled (List SideId) |
| 142 | `src/Types.elm:67-70` | - |
| 143 | `src/Types.elm:71-74` | } |
| 144 | `src/Types.elm:75` | } |
| 145 | `src/Types.elm:76` | | LobbyIsFull |
| 146 | `src/Types.elm:77-79` | | LobbyKilled |
| 147 | `src/Types.elm:80-82` | } |
| 148 | `src/Types.elm:83-85` | } |
| 149 | `src/Types.elm:86` | } |
| 151 | `src/Backend.elm:99-102` | in |
| 154 | `src/Frontend.elm:162-169` | case model of |
| 156 | `src/Views/PlayerLobbyView.elm:11-39` | - |
| 157 | `src/Views/GameView.elm:58-90` | ] |
| 157 | `src/Views/GameView.elm:92-157` | - |
| 157 | `src/Views/GameView.elm:740-745` | , br [] [] |
| 162 | `tests/GameLogicTests.elm:14-56` | - |
| 162 | `tests/GameLogicTests.elm:60-225` | - |
| 162 | `tests/MeepleTests.elm:47-58` | Expect.equal (getFeatureOwners meeples 0) [ 1 ] |
| 162 | `tests/MeepleTests.elm:12` | - |
| 162 | `src/Helpers/GameLogic.elm:1-556` | module Helpers.GameLogic exposing (..) |
| 163 | `.github/workflows/test.yaml:39-43` | - |
| 165 | `.github/workflows/test.yaml:30-37` | - |
| 169 | `.github/workflows/test.yaml:46` | - name: Run unit tests |
| 191 | `readme.md:129` | - |
| 191 | `src/Views/GameView.elm:582` | , style "min-height" "100vh" |
| 192 | `src/Views/GameView.elm:694` | ] |
| 193 | `src/Backend.elm:73` | ( BeGamePlayed { game = updatedGame } |

Density warnings: § 11. Cross-References to Sibling Models (no citations)

## ClassModel.md

**Status: PASS** - citations 433/433 ok; mermaid blocks: 2 (classDiagram, classDiagram)

### Resolved citations (verify by eye against the code)
| Doc line | Citation | Context at cited line |
| --: | :-- | :-- |
| 5 | `src/Frontend.elm:17-31` | - |
| 5 | `elm.json:6` | ], |
| 5 | `src/Backend.elm:18-25` | - |
| 5 | `elm.json:17-18` | "elm-explorations/test": "2.2.0", |
| 5 | `src/Evergreen/Migrate/V10.elm:3` | - |
| 18 | `src/Helpers/TileMapper.elm:1` | module Helpers.TileMapper exposing (getTile) |
| 18 | `src/Frontend.elm:1` | module Frontend exposing (Model, app) |
| 24 | `src/Types/Game.elm:28-40` | - |
| 25 | `src/Types/Tile.elm:21-29` | - |
| 26 | `src/Types/Tile.elm:15-18` | - |
| 27 | `src/Types/Tile.elm:7-8` | - |
| 28 | `src/Types/Tile.elm:11-12` | - |
| 29 | `src/Types/Game.elm:20-21` | - |
| 30 | `src/Types/Game.elm:16-17` | - |
| 31 | `src/Types/Game.elm:24-25` | - |
| 32 | `src/Types/Meeple.elm:17-23` | - |
| 33 | `src/Types/Meeple.elm:8-14` | - |
| 34 | `src/Types/Feature.elm:4-8` | - |
| 35 | `src/Types/GameState.elm:4-7` | - |
| 36 | `src/Types/Coordinate.elm:4-5` | - |
| 37 | `src/Types/PlayerIndex.elm:4-5` | - |
| 38 | `src/Types/PlayerName.elm:4-5` | - |
| 39 | `src/Types/Score.elm:4-5` | - |
| 40 | `src/Types.elm:20-33` | - |
| 41 | `src/Types.elm:11-17` | - |
| 42 | `src/Types.elm:36-47` | - |
| 43 | `src/Types.elm:50-58` | - |
| 44 | `src/Types.elm:61-65` | - |
| 45 | `src/Types.elm:67-86` | - |
| 46 | `src/Helpers/GameLogic.elm:1` | module Helpers.GameLogic exposing (..) |
| 48 | `src/Helpers/FrontendHelpers.elm:1` | module Helpers.FrontendHelpers exposing (..) |
| 50 | `src/Backend.elm:1` | module Backend exposing (..) |
| 51 | `src/Views/GameView.elm:1` | module Views.GameView exposing (..) |
| 52 | `src/Views/PlayerLobbyView.elm:1` | module Views.PlayerLobbyView exposing (..) |
| 53 | `src/Views/PlayerRegistrationView.elm:1` | module Views.PlayerRegistrationView exposing (..) |
| 54 | `src/Styles.elm:1` | module Styles exposing (..) |
| 56 | `tests/GameLogicTests.elm:1` | module GameLogicTests exposing (..) |
| 56 | `tests/MeepleTests.elm:1` | module MeepleTests exposing (..) |
| 62 | `src/Backend.elm:14-15` | - |
| 78 | `src/Types/Game.elm:29` | type alias Game = |
| 79 | `src/Types/Game.elm:30` | { playerScores : PlayerScores |
| 80 | `src/Types/Game.elm:31` | , playerMeeples : Dict PlayerName Int |
| 81 | `src/Types/Game.elm:32` | , players : Array PlayerName |
| 82 | `src/Types/Game.elm:33` | , currentPlayer : PlayerIndex |
| 83 | `src/Types/Game.elm:34` | , tileToPlace : Tile |
| 84 | `src/Types/Game.elm:35` | , gameState : GameState |
| 85 | `src/Types/Game.elm:36` | , lastPlacedTile : Coordinate |
| 86 | `src/Types/Game.elm:37` | , nextSideId : SideId |
| 87 | `src/Types/Game.elm:38` | , tileDrawStack : List TileId |
| 88 | `src/Types/Game.elm:39` | , tileGrid : TileGrid |
| 94 | `src/Types/Game.elm:53-73` | -} |
| 95 | `src/Types/Game.elm:78-84` | -} |
| 96 | `src/Types/Game.elm:89-94` | -} |
| 97 | `src/Types/Game.elm:102-104` | -} |
| 98 | `src/Types/Game.elm:109-115` | -} |
| 99 | `src/Types/Game.elm:120-147` | -} |
| 101 | `src/Types/Game.elm:43-45` | - |
| 101 | `src/Types/Game.elm:61` | { playerScores = Dict.fromList (List.map (\playerName -> ( playerName, 0 )) players) |
| 113 | `src/Types/Tile.elm:22` | type alias Tile = |
| 114 | `src/Types/Tile.elm:23` | { tileId : TileId |
| 115 | `src/Types/Tile.elm:24` | , rotation : Int |
| 116 | `src/Types/Tile.elm:25` | , north : Side |
| 117 | `src/Types/Tile.elm:26` | , east : Side |
| 118 | `src/Types/Tile.elm:27` | , south : Side |
| 119 | `src/Types/Tile.elm:28` | , west : Side |
| 125 | `src/Types/Tile.elm:34-37` | -} |
| 126 | `src/Types/Tile.elm:42-45` | -} |
| 127 | `src/Types/Tile.elm:50-57` | -} |
| 128 | `src/Types/Tile.elm:62-81` | -} |
| 129 | `src/Types/Tile.elm:84-86` | - |
| 131 | `src/Helpers/TileMapper.elm:17` | , east = { sideId = 1, sideFeature = Road } |
| 143 | `src/Types/Tile.elm:16` | type alias Side = |
| 144 | `src/Types/Tile.elm:17` | { sideId : SideId |
| 228 | `src/Types/Meeple.elm:18` | type alias Meeple = |
| 229 | `src/Types/Meeple.elm:19` | { owner : PlayerIndex |
| 230 | `src/Types/Meeple.elm:20` | , coordinates : Coordinate |
| 236 | `src/Types/Meeple.elm:37-42` | - |
| 238 | `src/Types/Meeple.elm:26-34` | - |
| 238 | `src/Types/Meeple.elm:22` | - |
| 250 | `src/Types/Meeple.elm:9` | type MeeplePosition |
| 251 | `src/Types/Meeple.elm:10` | = Center |
| 252 | `src/Types/Meeple.elm:11` | | North |
| 253 | `src/Types/Meeple.elm:12` | | East |
| 254 | `src/Types/Meeple.elm:13` | | South |
| 255 | `src/Types/Meeple.elm:14` | | West |
| 257 | `src/Helpers/GameLogic.elm:412-413` | - |
| 269 | `src/Types/Feature.elm:5` | type Feature |
| 270 | `src/Types/Feature.elm:6` | = City |
| 271 | `src/Types/Feature.elm:7` | | Road |
| 272 | `src/Types/Feature.elm:8` | | Field |
| 286 | `src/Types/GameState.elm:5` | type GameState |
| 287 | `src/Types/GameState.elm:6` | = PlaceTileState |
| 288 | `src/Types/GameState.elm:7` | | PlaceMeepleState |
| 294 | `src/Types/GameState.elm:10-20` | - |
| 354 | `src/Helpers/GameLogic.elm:323-370` | -} |
| 354 | `src/Helpers/GameLogic.elm:383-508` | -} |
| 354 | `src/Helpers/GameLogic.elm:511-556` | - |
| 372 | `src/Helpers/GameLogic.elm:21-40` | -} |
| 373 | `src/Helpers/GameLogic.elm:45-94` | -} |
| 374 | `src/Helpers/GameLogic.elm:102-131` | -} |
| 375 | `src/Helpers/GameLogic.elm:136-162` | -} |
| 376 | `src/Helpers/GameLogic.elm:170-188` | -} |
| 377 | `src/Helpers/GameLogic.elm:193-203` | -} |
| 378 | `src/Helpers/GameLogic.elm:211-224` | -} |
| 379 | `src/Helpers/GameLogic.elm:230-251` | -} |
| 380 | `src/Helpers/GameLogic.elm:256-290` | -} |
| 381 | `src/Helpers/GameLogic.elm:300-308` | -} |
| 386 | `src/Helpers/GameLogic.elm:367` | , nextSideId = getTileMaximumSideId tileToPlace |
| 386 | `src/Helpers/GameLogic.elm:507` | , playerScores = playerScores |
| 386 | `src/Helpers/GameLogic.elm:430-432` | in |
| 386 | `src/Helpers/GameLogic.elm:493-500` | finishedFeatureScores |
| 400 | `src/Helpers/TileMapper.elm:9-253` | -} |
| 402 | `src/Helpers/TileMapper.elm:49` | , west = { sideId = -1, sideFeature = Field } |
| 402 | `src/Helpers/TileMapper.elm:59` | , west = { sideId = -1, sideFeature = Field } |
| 402 | `src/Helpers/TileMapper.elm:252-253` | - |
| 416 | `src/Helpers/FrontendHelpers.elm:16-22` | -} |
| 417 | `src/Helpers/FrontendHelpers.elm:27-43` | -} |
| 418 | `src/Helpers/FrontendHelpers.elm:48-84` | -} |
| 419 | `src/Helpers/FrontendHelpers.elm:89-110` | -} |
| 420 | `src/Helpers/FrontendHelpers.elm:120-127` | -} |
| 421 | `src/Helpers/FrontendHelpers.elm:132-143` | -} |
| 423 | `src/Helpers/FrontendHelpers.elm:67-84` | in |
| 423 | `src/Helpers/FrontendHelpers.elm:42-43` | - |
| 442 | `src/Backend.elm:28-34` | - |
| 443 | `src/Backend.elm:37-87` | - |
| 444 | `src/Backend.elm:90-186` | - |
| 445 | `src/Backend.elm:189-191` | - |
| 447 | `src/Backend.elm:110-118` | in |
| 447 | `src/Backend.elm:120-123` | - |
| 447 | `src/Backend.elm:76-84` | - |
| 455 | `src/Frontend.elm:13-14` | - |
| 462 | `src/Frontend.elm:34-41` | - |
| 463 | `src/Frontend.elm:44-89` | - |
| 464 | `src/Frontend.elm:92-156` | - |
| 465 | `src/Frontend.elm:159-169` | - |
| 467 | `src/Frontend.elm:18-31` | app : { init : Lamdera.Url -> Key -> ( Model, Cmd FrontendMsg ), view : Model -> Document FrontendMs |
| 467 | `src/Frontend.elm:28` | } |
| 467 | `src/Frontend.elm:29-30` | , subscriptions = \_ -> Sub.none |
| 467 | `src/Frontend.elm:50-62` | - |
| 489 | `src/Types.elm:51` | type ToBackend |
| 490 | `src/Types.elm:52` | = RegisterPlayer PlayerName |
| 491 | `src/Types.elm:53` | | KickPlayer PlayerName |
| 492 | `src/Types.elm:54` | | KillLobby |
| 493 | `src/Types.elm:55` | | InitializeGame |
| 494 | `src/Types.elm:56` | | RotateTileLeft |
| 495 | `src/Types.elm:57` | | PlaceTile Coordinate |
| 496 | `src/Types.elm:58` | | PlaceMeeple MeeplePosition |
| 510 | `src/Types.elm:68-70` | type ToFrontend |
| 511 | `src/Types.elm:71-74` | } |
| 512 | `src/Types.elm:75` | } |
| ... | 283 more | |

Density warnings: § 10. Sources & Cross-References (no citations)

## DatabaseModel.md

**Status: PASS** - citations 372/372 ok; mermaid blocks: 1 (erDiagram)

### Resolved citations (verify by eye against the code)
| Doc line | Citation | Context at cited line |
| --: | :-- | :-- |
| 12 | `src/Backend.elm:14-15` | - |
| 16 | `src/Types.elm:11-17` | - |
| 17 | `src/Backend.elm:18-25` | - |
| 17 | `src/Types/Tile.elm:28` | , west : Side |
| 17 | `src/Types.elm:23` | { nameInput : String |
| 18 | `readme.md:139-151` | - |
| 18 | `.github/workflows/test.yaml:33-34` | - |
| 20 | `src/Evergreen/Migrate/V10.elm:3` | - |
| 24 | `src/Types/Game.elm:28` | - |
| 24 | `src/Types/Tile.elm:21` | - |
| 24 | `src/Types/Meeple.elm:17` | - |
| 24 | `src/Types.elm:11` | - |
| 24 | `src/Types/Game.elm:16-25` | - |
| 25 | `src/Types/Game.elm:29-39` | type alias Game = |
| 25 | `src/Types/PlayerName.elm:4-5` | - |
| 25 | `src/Types/Score.elm:4-5` | - |
| 25 | `src/Types/Coordinate.elm:4-5` | - |
| 25 | `src/Types/PlayerIndex.elm:4-5` | - |
| 26 | `src/Types/Game.elm:20-21` | - |
| 26 | `src/Types/Game.elm:16-17` | - |
| 26 | `src/Types/Game.elm:24-25` | - |
| 26 | `src/Helpers/TileMapper.elm:9-12` | -} |
| 26 | `src/Helpers/TileMapper.elm:252-253` | - |
| 27 | `src/Types/Meeple.elm:18` | type alias Meeple = |
| 27 | `src/Types/Game.elm:31` | , playerMeeples : Dict PlayerName Int |
| 28 | `src/Types.elm:31` | { playerName : PlayerName |
| 29 | `src/Types/Game.elm:28-40` | - |
| 144 | `src/Types.elm:20-33` | - |
| 149 | `src/Types/Tile.elm:21-29` | - |
| 150 | `src/Types/Tile.elm:15-18` | - |
| 151 | `src/Types/Meeple.elm:17-23` | - |
| 152 | `src/Types/Feature.elm:4-8` | - |
| 153 | `src/Types/GameState.elm:4-7` | - |
| 154 | `src/Types/Meeple.elm:8-14` | - |
| 159 | `src/Types.elm:13` | = BePlayerRegistration |
| 160 | `src/Types.elm:16` | | BeGamePlayed |
| 161 | `src/Types.elm:22` | = FePlayerRegistration |
| 163 | `src/Types.elm:26` | | FeLobby |
| 164 | `src/Types.elm:27` | { playerName : PlayerName |
| 165 | `src/Types.elm:30` | | FeGamePlayed |
| 167 | `src/Types.elm:32` | , debugMode : Bool |
| 168 | `src/Types/Game.elm:29` | type alias Game = |
| 169 | `src/Types/Game.elm:30` | { playerScores : PlayerScores |
| 169 | `src/Types/Game.elm:61` | { playerScores = Dict.fromList (List.map (\playerName -> ( playerName, 0 )) players) |
| 171 | `src/Types/Game.elm:32` | , players : Array PlayerName |
| 171 | `src/Types/Game.elm:78-84` | -} |
| 172 | `src/Types/Game.elm:33` | , currentPlayer : PlayerIndex |
| 172 | `src/Backend.elm:44-59` | - |
| 173 | `src/Types/Game.elm:34` | , tileToPlace : Tile |
| 174 | `src/Types/Game.elm:35` | , gameState : GameState |
| 175 | `src/Types/Game.elm:36` | , lastPlacedTile : Coordinate |
| 175 | `src/Types/Game.elm:109-115` | -} |
| 176 | `src/Helpers/GameLogic.elm:511-556` | - |
| 176 | `src/Types/Game.elm:37` | , nextSideId : SideId |
| 176 | `src/Backend.elm:76-84` | - |
| 177 | `src/Types/Game.elm:38` | , tileDrawStack : List TileId |
| 177 | `src/Types/Game.elm:102-104` | -} |
| 178 | `src/Types/Game.elm:39` | , tileGrid : TileGrid |
| 185 | `src/Types/Tile.elm:22` | type alias Tile = |
| 186 | `src/Types/Tile.elm:23` | { tileId : TileId |
| 186 | `src/Helpers/GameLogic.elm:24-31` | -- Prevent problems with overflow |
| 187 | `src/Types/Tile.elm:24` | , rotation : Int |
| 188 | `src/Types/Tile.elm:25` | , north : Side |
| 189 | `src/Types/Tile.elm:26` | , east : Side |
| 190 | `src/Types/Tile.elm:27` | , south : Side |
| 191 | `src/Helpers/TileMapper.elm:49` | , west = { sideId = -1, sideFeature = Field } |
| 191 | `src/Helpers/TileMapper.elm:59` | , west = { sideId = -1, sideFeature = Field } |
| 192 | `src/Types/Tile.elm:16` | type alias Side = |
| 192 | `src/Types/Tile.elm:62-81` | -} |
| 193 | `src/Types/Tile.elm:17` | { sideId : SideId |
| 195 | `src/Types/Meeple.elm:19` | { owner : PlayerIndex |
| 196 | `src/Types/Meeple.elm:20` | , coordinates : Coordinate |
| 201 | `tests/MeepleTests.elm:29` | Dict.fromList |
| 202 | `src/Types/Game.elm:43-45` | - |
| 203 | `src/Backend.elm:95-101` | let |
| 205 | `src/Types.elm:12-14` | type BackendModel |
| 205 | `src/Backend.elm:110-118` | in |
| 206 | `src/Types.elm:29-33` | } |
| 207 | `src/Types.elm:25-28` | } |
| 214 | `src/Types/Game.elm:87-94` | - |
| 216 | `src/Types/Tile.elm:24-27` | , rotation : Int |
| 216 | `src/Helpers/GameLogic.elm:24-40` | -- Prevent problems with overflow |
| 218 | `src/Types/Tile.elm:16-17` | type alias Side = |
| 219 | `src/Helpers/GameLogic.elm:256-262` | -} |
| 329 | `src/Types/Game.elm:60` | in |
| 331 | `src/Types/Game.elm:48-51` | - |
| 335 | `src/Helpers/GameLogic.elm:393-413` | - |
| 337 | `src/Backend.elm:147` | ( BeGamePlayed { game = game } |
| 337 | `src/Backend.elm:177` | ( BeGamePlayed { game = updatedGame } |
| 358 | `src/Helpers/GameLogic.elm:401-413` | North -> |
| 366 | `src/Helpers/GameLogic.elm:21-40` | -} |
| 448 | `src/Backend.elm:93-97` | case ( msg, model ) of |
| 551 | `src/Helpers/GameLogic.elm:350` | game.tileGrid |
| 554 | `src/Helpers/GameLogic.elm:480` | in |
| 555 | `src/Types/Game.elm:31-32` | , playerMeeples : Dict PlayerName Int |
| 555 | `src/Backend.elm:110` | in |
| 557 | `src/Backend.elm:125-133` | - |
| 558 | `src/Helpers/GameLogic.elm:198-201` | (\( ( x, y ), tile ) -> |
| 558 | `src/Helpers/GameLogic.elm:232-240` | getAdjacentTileCloisterScores grid ( x, y ) = |
| 558 | `src/Helpers/GameLogic.elm:333-350` | northernAdjacentSideId = |
| 558 | `src/Types/Game.elm:89-94` | -} |
| 559 | `tests/MeepleTests.elm:14-70` | getFeatureOwnersTest = |
| 560 | `src/Types/Meeple.elm:26-42` | - |
| 570 | `src/Evergreen/Migrate/V3.elm:27-54` | - |
| 570 | `src/Evergreen/Migrate/V10.elm:36-63` | - |
| 578 | `src/Helpers/TileMapper.elm:9-253` | -} |
| 579 | `src/Types/Game.elm:120-147` | -} |
| 581 | `src/Types/Game.elm:53-73` | -} |
| 582 | `src/Backend.elm:28-34` | - |
| 622 | `src/Evergreen/V1/Types.elm:7-49` | - |
| 622 | `src/Evergreen/V3/Types/Game.elm:21-41` | - |
| 622 | `src/Evergreen/Migrate/V5.elm:36-43` | - |
| 622 | `src/Evergreen/V5/Types/Game.elm:30-41` | - |
| 622 | `src/Evergreen/V10/Types/Game.elm:26-38` | - |
| 639 | `src/Evergreen/Migrate/V10.elm:3-18` | - |
| 639 | `elm.json:17-18` | "elm-explorations/test": "2.2.0", |
| 642 | `src/Evergreen/V10/Types.elm:66` | | TileDrawStackShuffled (List Evergreen.V10.Types.Tile.SideId) |
| 642 | `src/Evergreen/V10/Types.elm:47` | | FeTerminateGame |
| 642 | `src/Types.elm:61-64` | - |
| 642 | `src/Types.elm:36-47` | - |
| 644 | `src/Types/Game.elm:65-66` | - |

## DomainModel.md

**Status: PASS** - citations 307/307 ok; mermaid blocks: 1 (classDiagram)

### Resolved citations (verify by eye against the code)
| Doc line | Citation | Context at cited line |
| --: | :-- | :-- |
| 12 | `elm.json:6` | ], |
| 12 | `elm.json:17-18` | "elm-explorations/test": "2.2.0", |
| 12 | `src/Backend.elm:18-25` | - |
| 13 | `src/Types/Game.elm:28-40` | - |
| 13 | `src/Helpers/GameLogic.elm:323-508` | -} |
| 13 | `src/Backend.elm:160-183` | - |
| 15 | `src/Helpers/GameLogic.elm:1-556` | module Helpers.GameLogic exposing (..) |
| 15 | `src/Helpers/TileMapper.elm:9-253` | -} |
| 15 | `src/Backend.elm:93-186` | case ( msg, model ) of |
| 16 | `src/Evergreen/Migrate/V10.elm:3` | - |
| 16 | `src/Backend.elm:14-15` | - |
| 24 | `src/Types/Tile.elm:21-29` | - |
| 24 | `readme.md:97-103` | - |
| 25 | `src/Types/Game.elm:102-104` | -} |
| 25 | `src/Types/Game.elm:120-147` | -} |
| 26 | `src/Types/Feature.elm:4-8` | - |
| 26 | `src/Helpers/TileMapper.elm:12-20` | case tileId of |
| 27 | `src/Types/Tile.elm:11-12` | - |
| 27 | `src/Types/Tile.elm:62-81` | -} |
| 27 | `src/Helpers/GameLogic.elm:102-131` | -} |
| 27 | `readme.md:101` | - |
| 28 | `src/Types/Meeple.elm:17-23` | - |
| 28 | `readme.md:105-112` | - |
| 29 | `readme.md:89-91` | - |
| 29 | `src/Types/Game.elm:31` | , playerMeeples : Dict PlayerName Int |
| 29 | `src/Types/Meeple.elm:26-34` | - |
| 31 | `src/Types/Game.elm:20-21` | - |
| 32 | `src/Types/Coordinate.elm:4-5` | - |
| 32 | `src/Types/Game.elm:104` | initializeTileGrid = |
| 33 | `src/Types/Game.elm:37` | , nextSideId : SideId |
| 33 | `src/Backend.elm:140-148` | - |
| 33 | `src/Backend.elm:170-178` | - |
| 34 | `readme.md:56-62` | - |
| 34 | `src/Helpers/GameLogic.elm:367` | , nextSideId = getTileMaximumSideId tileToPlace |
| 34 | `src/Helpers/GameLogic.elm:502-508` | in |
| 34 | `src/Types/Game.elm:78-84` | -} |
| 35 | `src/Types/GameState.elm:4-7` | - |
| 35 | `readme.md:113-117` | - |
| 36 | `src/Types/Game.elm:35` | , gameState : GameState |
| 36 | `src/Types/Game.elm:89-94` | -} |
| 37 | `src/Types/Tile.elm:28` | , west : Side |
| 37 | `src/Types/Tile.elm:52-57` | getAllSides tile = |
| 37 | `src/Helpers/GameLogic.elm:211-251` | -} |
| 38 | `src/Helpers/GameLogic.elm:193-203` | -} |
| 38 | `src/Helpers/GameLogic.elm:418-422` | - |
| 39 | `src/Helpers/GameLogic.elm:256-290` | -} |
| 39 | `tests/MeepleTests.elm:47-58` | Expect.equal (getFeatureOwners meeples 0) [ 1 ] |
| 39 | `readme.md:66-68` | - |
| 40 | `src/Types/Score.elm:4-5` | - |
| 40 | `src/Types/Game.elm:29` | type alias Game = |
| 41 | `src/Types.elm:11-17` | - |
| 41 | `src/Backend.elm:93-148` | case ( msg, model ) of |
| 50 | `src/Helpers/GameLogic.elm:323-370` | -} |
| 50 | `src/Helpers/GameLogic.elm:383-508` | -} |
| 51 | `src/Types.elm:15-17` | } |
| 54 | `src/Backend.elm:93-138` | case ( msg, model ) of |
| 54 | `src/Types.elm:20-33` | - |
| 55 | `src/Types.elm:12-14` | type BackendModel |
| 57 | `src/Backend.elm:120-123` | - |
| 68 | `src/Backend.elm:14-34` | - |
| 71 | `src/Types/Game.elm:53-73` | -} |
| 74 | `src/Helpers/GameLogic.elm:511-556` | - |
| 75 | `src/Backend.elm:150-158` | - |
| 76 | `src/Backend.elm:44-74` | - |
| 79 | `src/Types/Tile.elm:22` | type alias Tile = |
| 82 | `src/Helpers/GameLogic.elm:21-40` | -} |
| 84 | `src/Helpers/GameLogic.elm:45-95` | -} |
| 84 | `tests/GameLogicTests.elm:14-56` | - |
| 87 | `src/Types/Game.elm:24-25` | - |
| 87 | `src/Types/Game.elm:39` | , tileGrid : TileGrid |
| 90 | `src/Helpers/GameLogic.elm:397-416` | - |
| 91 | `src/Helpers/GameLogic.elm:136-162` | -} |
| 92 | `src/Helpers/GameLogic.elm:470-492` | - |
| 93 | `src/Helpers/GameLogic.elm:554` | | playerScores = playerScores |
| 95 | `src/Types/Game.elm:29-32` | type alias Game = |
| 99 | `src/Backend.elm:93-118` | case ( msg, model ) of |
| 100 | `src/Backend.elm:125-133` | - |
| 101 | `src/Helpers/GameLogic.elm:444-464` | - |
| 101 | `src/Helpers/GameLogic.elm:529-550` | - |
| 102 | `src/Helpers/GameLogic.elm:482-500` | - |
| 110 | `src/Helpers/GameLogic.elm:431` | -- Cities that are larger than 2 tiles give 2x points if they are completed before the game ends |
| 111 | `src/Types/Tile.elm:15-18` | - |
| 111 | `src/Helpers/GameLogic.elm:109-115` | - |
| 114 | `src/Types/PlayerIndex.elm:4-5` | - |
| 115 | `src/Types/PlayerName.elm:4-5` | - |
| 117 | `src/Types/Tile.elm:7-8` | - |
| 118 | `src/Types/Meeple.elm:8-14` | - |
| 124 | `src/Helpers/GameLogic.elm:364-370` | in |
| 126 | `src/Types/Game.elm:38` | , tileDrawStack : List TileId |
| 132 | `src/Backend.elm:58` | ( BeGamePlayed { game = updatedGame } |
| 143 | `src/Types/Game.elm:43-45` | - |
| 145 | `src/Helpers/GameLogic.elm:331-362` | - |
| 146 | `src/Types/Meeple.elm:18` | type alias Meeple = |
| 146 | `src/Types/Game.elm:30` | { playerScores : PlayerScores |
| 148 | `src/Types/Game.elm:34` | , tileToPlace : Tile |
| 148 | `src/Helpers/GameLogic.elm:10` | import Types.Feature exposing (Feature(..)) |
| 148 | `src/Helpers/GameLogic.elm:5` | import Dict exposing (Dict) |
| 267 | `src/Helpers/FrontendHelpers.elm:48-85` | -} |
| 267 | `src/Helpers/FrontendHelpers.elm:89-110` | -} |
| 267 | `src/Views/GameView.elm:58-75` | ] |
| 267 | `src/Views/GameView.elm:318-333` | - |
| 267 | `src/Helpers/GameLogic.elm:311-315` | - |
| 268 | `src/Helpers/FrontendHelpers.elm:120-143` | -} |
| 268 | `src/Backend.elm:44-59` | - |
| 268 | `src/Backend.elm:61-74` | - |
| 272 | `src/Helpers/GameLogic.elm:426-435` | let |
| 272 | `src/Helpers/GameLogic.elm:170-188` | -} |
| 272 | `src/Helpers/GameLogic.elm:431-432` | -- Cities that are larger than 2 tiles give 2x points if they are completed before the game ends |
| 272 | `readme.md:71` | - Completed Road is worth 1 points per each tile. |
| 273 | `src/Helpers/GameLogic.elm:211-224` | -} |
| 273 | `src/Helpers/GameLogic.elm:230-251` | -} |
| 273 | `src/Helpers/GameLogic.elm:438` | -- Append cloister score if exists |
| 274 | `src/Helpers/GameLogic.elm:511-527` | - |
| 276 | `src/Helpers/FrontendHelpers.elm:27-43` | -} |
| 276 | `src/Views/GameView.elm:524-539` | - |
| 276 | `src/Helpers/GameLogic.elm:373-382` | - |
| 277 | `src/Types/Game.elm:61` | { playerScores = Dict.fromList (List.map (\playerName -> ( playerName, 0 )) players) |
| 277 | `src/Helpers/GameLogic.elm:493-500` | finishedFeatureScores |
| 277 | `src/Helpers/FrontendHelpers.elm:28-43` | getMeeplePositionsToBePlacedOn : PlayerName -> Dict PlayerName Int -> Meeples -> Tile -> List Meeple |
| 279 | `src/Helpers/FrontendHelpers.elm:132-143` | -} |
| 279 | `src/Backend.elm:76-84` | - |
| 279 | `src/Helpers/GameLogic.elm:552-556` | in |
| 279 | `readme.md:74` | - |
| 280 | `src/Backend.elm:95-102` | let |
| 280 | `src/Backend.elm:110-118` | in |
| 280 | `src/Frontend.elm:50-57` | - |
| 281 | `readme.md:79` | - Incomplete Cloister is worth 1 for adjacent tile + 1 point for itself. |
| 281 | `src/Types/Tile.elm:42-45` | -} |
| 281 | `src/Helpers/GameLogic.elm:172-173` | countFeature tileGrid sideId = |
| 282 | `readme.md:61` | 1) Draw 1 tile and place it on the board. If it can not be placed, shuffle it back and draw a new on |
| 282 | `src/Helpers/FrontendHelpers.elm:33-40` | |> List.filter (\( sideId, _ ) -> Dict.get sideId meeples == Nothing) |
| 283 | `readme.md:129` | - |
| 283 | `src/Views/GameView.elm:542-590` | - |
| 283 | `src/Views/GameView.elm:64-75` | in |
| 283 | `src/Views/GameView.elm:131-142` | in |
| 291 | `src/Backend.elm:105-113` | else |
| 291 | `src/Backend.elm:40-42` | case ( msg, model ) of |
| 291 | `src/Backend.elm:99-102` | in |
| 291 | `src/Frontend.elm:95-96` | case ( msg, model ) of |
| 291 | `src/Types.elm:67-70` | - |
| 292 | `src/Frontend.elm:98-105` | - |
| 292 | `src/Types.elm:71-74` | } |
| 293 | `src/Backend.elm:135-138` | - |
| 293 | `src/Frontend.elm:117-123` | - |
| 293 | `src/Types.elm:76` | | LobbyIsFull |
| 294 | `src/Frontend.elm:134-141` | - |
| 294 | `src/Types.elm:77-79` | | LobbyKilled |
| 295 | `src/Frontend.elm:143-150` | - |
| 296 | `src/Backend.elm:160-168` | - |
| 299 | `src/Backend.elm:180-183` | - |
| ... | 157 more | |

## UseCaseModel.md

**Status: PASS** - citations 346/346 ok; mermaid blocks: 1 (flowchart)

### Resolved citations (verify by eye against the code)
| Doc line | Citation | Context at cited line |
| --: | :-- | :-- |
| 23 | `src/Types/Feature.elm:1-8` | module Types.Feature exposing (..) |
| 23 | `src/Types/Tile.elm:28` | , west : Side |
| 23 | `src/Helpers/GameLogic.elm:326-362` | let |
| 24 | `src/Types/Tile.elm:1-57` | module Types.Tile exposing (..) |
| 24 | `src/Helpers/GameLogic.elm:331-362` | - |
| 25 | `src/Types/Meeple.elm:1-23` | module Types.Meeple exposing (..) |
| 26 | `src/Types/Tile.elm:42-57` | -} |
| 26 | `src/Helpers/GameLogic.elm:211-251` | -} |
| 27 | `src/Types/Game.elm:120-147` | -} |
| 27 | `src/Backend.elm:177` | ( BeGamePlayed { game = updatedGame } |
| 28 | `src/Types/GameState.elm:4-7` | - |
| 29 | `src/Types.elm:11-14` | - |
| 29 | `src/Backend.elm:28-34` | - |
| 30 | `src/Types.elm:15-17` | } |
| 31 | `src/Types.elm:50-58` | - |
| 31 | `src/Types.elm:67-86` | - |
| 32 | `src/Backend.elm:6` | import Helpers.TileMapper exposing (getTile) |
| 32 | `src/Backend.elm:189-191` | - |
| 43 | `src/Types.elm:51` | type ToBackend |
| 44 | `src/Types.elm:52` | = RegisterPlayer PlayerName |
| 45 | `src/Types.elm:53` | | KickPlayer PlayerName |
| 46 | `src/Types.elm:54` | | KillLobby |
| 47 | `src/Types.elm:55` | | InitializeGame |
| 48 | `src/Types.elm:56` | | RotateTileLeft |
| 49 | `src/Types.elm:57` | | PlaceTile Coordinate |
| 50 | `src/Types.elm:58` | | PlaceMeeple MeeplePosition |
| 51 | `src/Types.elm:68-70` | type ToFrontend |
| 52 | `src/Types.elm:71-74` | } |
| 53 | `src/Types.elm:75` | } |
| 54 | `src/Types.elm:76` | | LobbyIsFull |
| 55 | `src/Types.elm:77-79` | | LobbyKilled |
| 56 | `src/Types.elm:80-82` | } |
| 56 | `src/Frontend.elm:143-150` | - |
| 57 | `src/Types.elm:83-85` | } |
| 58 | `src/Types.elm:86` | } |
| 62 | `src/Views/PlayerLobbyView.elm:30-37` | ul Styles.playerList |
| 62 | `src/Views/PlayerLobbyView.elm:20-23` | , renderPlayerNames players |
| 62 | `src/Backend.elm:125-133` | - |
| 62 | `src/Backend.elm:140-148` | - |
| 62 | `src/Views/PlayerRegistrationView.elm:29-37` | ] |
| 66 | `src/Frontend.elm:4` | import Html exposing (Html) |
| 107 | `src/Views/PlayerLobbyView.elm:20-37` | , renderPlayerNames players |
| 110 | `src/Backend.elm:93-118` | case ( msg, model ) of |
| 113 | `src/Helpers/GameLogic.elm:323-370` | -} |
| 114 | `src/Helpers/GameLogic.elm:21-40` | -} |
| 115 | `src/Helpers/GameLogic.elm:383-508` | -} |
| 116 | `src/Helpers/GameLogic.elm:256-290` | -} |
| 117 | `src/Backend.elm:120-123` | - |
| 137 | `src/Backend.elm:110-113` | in |
| 138 | `src/Frontend.elm:60-61` | else |
| 144 | `src/Views/PlayerRegistrationView.elm:17-24` | [ onSubmit Register ] |
| 145 | `src/Frontend.elm:47-48` | case ( msg, model ) of |
| 146 | `src/Views/PlayerRegistrationView.elm:16` | [ Html.form |
| 146 | `src/Views/PlayerRegistrationView.elm:25-28` | [] |
| 147 | `src/Frontend.elm:50-62` | - |
| 148 | `src/Backend.elm:95-108` | let |
| 149 | `src/Backend.elm:111-113` | if List.length newPlayers <= playerLimit then |
| 150 | `src/Frontend.elm:95-96` | case ( msg, model ) of |
| 150 | `src/Views/PlayerLobbyView.elm:18-19` | , br [] [] |
| 156 | `src/Frontend.elm:56-57` | in |
| 156 | `src/Views/PlayerRegistrationView.elm:40-45` | ] |
| 157 | `src/Backend.elm:99-102` | in |
| 157 | `src/Views/PlayerLobbyView.elm:11-24` | - |
| 158 | `src/Backend.elm:110-118` | in |
| 158 | `src/Types/Game.elm:43-45` | - |
| 158 | `src/Frontend.elm:107-115` | - |
| 161 | `src/Backend.elm:110` | in |
| 162 | `src/Types/PlayerName.elm:4-5` | - |
| 162 | `src/Backend.elm:95-98` | let |
| 163 | `src/Frontend.elm:165-166` | - |
| 180 | `src/Backend.elm:129-133` | newPlayers = |
| 181 | `src/Frontend.elm:98-100` | - |
| 181 | `src/Frontend.elm:34-41` | - |
| 188 | `src/Frontend.elm:64-65` | - |
| 189 | `src/Backend.elm:125-130` | - |
| 190 | `src/Backend.elm:132` | ( BePlayerRegistration { players = newPlayers } |
| 191 | `src/Frontend.elm:98-105` | - |
| 215 | `src/Types/Game.elm:48-52` | - |
| 218 | `src/Backend.elm:146` | in |
| 219 | `src/Frontend.elm:134-141` | - |
| 219 | `src/Views/GameView.elm:28-29` | in |
| 226 | `src/Frontend.elm:67-68` | - |
| 227 | `src/Backend.elm:140-144` | - |
| 227 | `src/Types/Game.elm:53-73` | -} |
| 227 | `src/Types/Game.elm:102-104` | -} |
| 228 | `src/Backend.elm:147` | ( BeGamePlayed { game = game } |
| 229 | `src/Types.elm:63` | = ClientConnected SessionId ClientId |
| 229 | `src/Backend.elm:44` | - |
| 230 | `src/Backend.elm:46-54` | let |
| 230 | `src/Helpers/FrontendHelpers.elm:132-143` | -} |
| 230 | `src/Helpers/FrontendHelpers.elm:120-127` | -} |
| 231 | `src/Backend.elm:58` | ( BeGamePlayed { game = updatedGame } |
| 232 | `src/Views/GameView.elm:21-27` | - |
| 232 | `src/Views/GameView.elm:641-749` | - |
| 235 | `src/Frontend.elm:60-62` | else |
| 238 | `src/Helpers/FrontendHelpers.elm:142-143` | - |
| 241 | `src/Types/Game.elm:61` | { playerScores = Dict.fromList (List.map (\playerName -> ( playerName, 0 )) players) |
| 243 | `src/Helpers/FrontendHelpers.elm:134-140` | getPlayableTileFromDrawstack tileGrid tileDrawStack = |
| 257 | `src/Types/GameState.elm:5` | type GameState |
| 257 | `src/Helpers/GameLogic.elm:507` | , playerScores = playerScores |
| 258 | `src/Views/GameView.elm:58-75` | ] |
| 258 | `src/Backend.elm:160-168` | - |
| 259 | `src/Types/Game.elm:33` | , currentPlayer : PlayerIndex |
| 262 | `src/Helpers/GameLogic.elm:347-362` | - |
| 263 | `src/Helpers/GameLogic.elm:364-370` | in |
| 263 | `src/Types/GameState.elm:6` | = PlaceTileState |
| 264 | `src/Backend.elm:166-167` | in |
| 270 | `src/Helpers/FrontendHelpers.elm:89-110` | -} |
| 270 | `src/Helpers/FrontendHelpers.elm:48-84` | -} |
| 271 | `src/Views/GameView.elm:318-329` | - |
| 272 | `src/Frontend.elm:76-77` | - |
| 273 | `src/Helpers/GameLogic.elm:326-329` | let |
| 273 | `src/Types/Tile.elm:62-81` | -} |
| 274 | `src/Helpers/GameLogic.elm:102-131` | -} |
| 274 | `src/Helpers/GameLogic.elm:136-162` | -} |
| 275 | `src/Types/Tile.elm:34-37` | -} |
| 277 | `src/Views/GameView.elm:92-142` | - |
| 280 | `src/Views/GameView.elm:59-70` | ++ (if playerName == currentPlayerName then |
| 280 | `src/Views/GameView.elm:318-332` | - |
| 284 | `src/Helpers/GameLogic.elm:311-314` | - |
| 284 | `src/Helpers/GameLogic.elm:347-354` | - |
| 287 | `src/Views/GameView.elm:320-329` | renderPlaceableCell coord coordinatesToBePlacedOn = |
| 302 | `src/Backend.elm:150` | - |
| 306 | `src/Backend.elm:156-157` | in |
| 312 | `src/Views/GameView.elm:740-742` | , br [] [] |
| 313 | `src/Frontend.elm:70-71` | - |
| 314 | `src/Backend.elm:150-158` | - |
| 316 | `src/Views/GameView.elm:727-734` | ] |
| 319 | `src/Backend.elm:61-74` | - |
| 322 | `src/Backend.elm:185-186` | - |
| 325 | `src/Helpers/GameLogic.elm:23-31` | rotateLeft tile = |
| 327 | `src/Helpers/GameLogic.elm:45-94` | -} |
| 327 | `tests/GameLogicTests.elm:14-56` | - |
| 341 | `src/Helpers/GameLogic.elm:367` | , nextSideId = getTileMaximumSideId tileToPlace |
| 342 | `src/Views/GameView.elm:121-142` | ] |
| 342 | `src/Helpers/GameLogic.elm:386-391` | let |
| 345 | `src/Helpers/GameLogic.elm:502-508` | in |
| 345 | `src/Types/Game.elm:78-84` | -} |
| 346 | `src/Helpers/GameLogic.elm:418-500` | - |
| 347 | `src/Backend.elm:61-84` | - |
| 353 | `src/Helpers/FrontendHelpers.elm:27-43` | -} |
| 353 | `src/Views/GameView.elm:524-536` | - |
| 354 | `src/Views/GameView.elm:533` | , style "background-color" "rgba(255, 74, 231, 0.67)" |
| 355 | `src/Frontend.elm:79-80` | - |
| 356 | `src/Helpers/GameLogic.elm:383-413` | -} |
| 356 | `src/Types/Meeple.elm:17-23` | - |
| 357 | `src/Helpers/GameLogic.elm:418-438` | - |
| 357 | `src/Types/Tile.elm:42-45` | -} |
| 357 | `src/Helpers/GameLogic.elm:193-203` | -} |
| 357 | `src/Helpers/GameLogic.elm:170-189` | -} |
| ... | 196 more | |

## ActivityDiagram.md

**Status: PASS** - citations 332/332 ok; mermaid blocks: 5 (flowchart, flowchart, flowchart, flowchart, flowchart)

### Resolved citations (verify by eye against the code)
| Doc line | Citation | Context at cited line |
| --: | :-- | :-- |
| 13 | `src/Views/GameView.elm:318-329` | - |
| 13 | `src/Backend.elm:160-168` | - |
| 13 | `src/Helpers/GameLogic.elm:323-370` | -} |
| 14 | `src/Views/GameView.elm:524-539` | - |
| 14 | `src/Views/GameView.elm:382-396` | rows |
| 14 | `src/Backend.elm:170-178` | - |
| 14 | `src/Helpers/GameLogic.elm:383-508` | -} |
| 14 | `src/Backend.elm:61-84` | - |
| 15 | `src/Views/PlayerLobbyView.elm:20-23` | , renderPlayerNames players |
| 15 | `src/Frontend.elm:67-68` | - |
| 15 | `src/Backend.elm:140-148` | - |
| 15 | `src/Backend.elm:44-59` | - |
| 15 | `src/Types/Game.elm:53-73` | -} |
| 16 | `src/Views/PlayerRegistrationView.elm:11-46` | - |
| 16 | `src/Frontend.elm:50-62` | - |
| 16 | `src/Backend.elm:93-118` | case ( msg, model ) of |
| 17 | `src/Helpers/GameLogic.elm:511-556` | - |
| 17 | `src/Backend.elm:180-183` | - |
| 19 | `src/Backend.elm:147` | ( BeGamePlayed { game = game } |
| 19 | `src/Backend.elm:177` | ( BeGamePlayed { game = updatedGame } |
| 29 | `src/Views/GameView.elm:320` | renderPlaceableCell coord coordinatesToBePlacedOn = |
| 29 | `src/Backend.elm:185-186` | - |
| 30 | `src/Frontend.elm:44-46` | - |
| 30 | `src/Backend.elm:37-39` | - |
| 36 | `src/Types.elm:11-17` | - |
| 42 | `src/Backend.elm:6` | import Helpers.TileMapper exposing (getTile) |
| 42 | `src/Backend.elm:37-38` | - |
| 52 | `src/Helpers/GameLogic.elm:367` | , nextSideId = getTileMaximumSideId tileToPlace |
| 52 | `src/Helpers/GameLogic.elm:502-508` | in |
| 52 | `src/Helpers/GameLogic.elm:552-555` | in |
| 62 | `src/Helpers/GameLogic.elm:311-322` | - |
| 69 | `src/Views/GameView.elm:58` | ] |
| 69 | `src/Views/GameView.elm:73-74` | - |
| 70 | `src/Views/GameView.elm:331-332` | - |
| 70 | `src/Helpers/FrontendHelpers.elm:48-85` | -} |
| 121 | `src/Views/GameView.elm:28-29` | in |
| 121 | `src/Types/GameState.elm:4-7` | - |
| 121 | `src/Views/GameView.elm:727-734` | ] |
| 122 | `src/Views/GameView.elm:58-59` | ] |
| 122 | `src/Views/GameView.elm:24-26` | let |
| 124 | `src/Views/GameView.elm:60-62` | let |
| 124 | `src/Helpers/FrontendHelpers.elm:89-110` | -} |
| 125 | `src/Views/GameView.elm:318-332` | - |
| 128 | `src/Frontend.elm:76-77` | - |
| 128 | `src/Types.elm:56` | | RotateTileLeft |
| 129 | `src/Backend.elm:160` | - |
| 131 | `src/Helpers/GameLogic.elm:102-131` | -} |
| 131 | `src/Helpers/GameLogic.elm:136-162` | -} |
| 132 | `src/Backend.elm:167` | ( BeGamePlayed { game = updatedGame } |
| 133 | `src/Frontend.elm:143-150` | - |
| 134 | `src/Frontend.elm:168-169` | - |
| 134 | `src/Views/GameView.elm:92-157` | - |
| 134 | `src/Views/GameView.elm:122-129` | ++ (if playerName == currentPlayerName then |
| 134 | `src/Helpers/FrontendHelpers.elm:27-43` | -} |
| 134 | `src/Views/GameView.elm:686-693` | [ text <| |
| 135 | `src/Types/GameState.elm:6` | = PlaceTileState |
| 144 | `src/Views/GameView.elm:58-62` | ] |
| 146 | `src/Views/GameView.elm:320-329` | renderPlaceableCell coord coordinatesToBePlacedOn = |
| 148 | `src/Backend.elm:160-164` | - |
| 159 | `src/Views/GameView.elm:140-141` | - |
| 160 | `src/Helpers/FrontendHelpers.elm:32-43` | |> List.map2 (\position sideId -> ( sideId, position )) [ North, East, South, West, Center ] |
| 160 | `src/Views/GameView.elm:538-539` | - |
| 162 | `src/Backend.elm:76-84` | - |
| 233 | `src/Helpers/GameLogic.elm:367-369` | , nextSideId = getTileMaximumSideId tileToPlace |
| 233 | `src/Views/GameView.elm:92-93` | - |
| 234 | `src/Views/GameView.elm:121-122` | ] |
| 239 | `src/Views/GameView.elm:533` | , style "background-color" "rgba(255, 74, 231, 0.67)" |
| 239 | `src/Views/GameView.elm:393` | , style "cursor" "pointer" |
| 240 | `src/Frontend.elm:79-80` | - |
| 240 | `src/Types.elm:57` | | PlaceTile Coordinate |
| 241 | `src/Backend.elm:170` | - |
| 243 | `src/Helpers/GameLogic.elm:384-416` | placeMeeple : Game -> MeeplePosition -> Game |
| 244 | `src/Helpers/GameLogic.elm:418-422` | - |
| 244 | `src/Helpers/GameLogic.elm:193-203` | -} |
| 244 | `src/Types/Tile.elm:42-45` | -} |
| 245 | `src/Helpers/GameLogic.elm:431-435` | -- Cities that are larger than 2 tiles give 2x points if they are completed before the game ends |
| 245 | `src/Helpers/GameLogic.elm:300-308` | -} |
| 246 | `src/Helpers/GameLogic.elm:418-450` | - |
| 246 | `src/Helpers/GameLogic.elm:170-188` | -} |
| 246 | `src/Helpers/GameLogic.elm:211-251` | -} |
| 246 | `src/Helpers/GameLogic.elm:256-290` | -} |
| 247 | `src/Helpers/GameLogic.elm:440-508` | - |
| 247 | `src/Types/Game.elm:78-84` | -} |
| 247 | `src/Types/Game.elm:61` | { playerScores = Dict.fromList (List.map (\playerName -> ( playerName, 0 )) players) |
| 248 | `src/Types.elm:64` | | InitializeGameAndTileDrawStackShuffled (List SideId) |
| 249 | `src/Backend.elm:61-63` | - |
| 249 | `src/Helpers/FrontendHelpers.elm:132-143` | -} |
| 249 | `src/Helpers/FrontendHelpers.elm:120-127` | -} |
| 250 | `src/Backend.elm:63-70` | case getPlayableTileFromDrawstack game.tileGrid shuffledTileDrawStack of |
| 250 | `src/Helpers/TileMapper.elm:9-10` | -} |
| 252 | `src/Backend.elm:73` | ( BeGamePlayed { game = updatedGame } |
| 252 | `src/Backend.elm:83` | ( BeGamePlayed { game = updatedGame } |
| 255 | `src/Views/GameView.elm:159-194` | - |
| 256 | `src/Views/GameView.elm:28-90` | in |
| 264 | `src/Views/GameView.elm:121` | ] |
| 265 | `src/Views/GameView.elm:121-129` | ] |
| 266 | `src/Views/GameView.elm:526` | renderMeepleCircle position positionsToBePlacedOn = |
| 267 | `src/Views/GameView.elm:526-534` | renderMeepleCircle position positionsToBePlacedOn = |
| 268 | `src/Helpers/FrontendHelpers.elm:42-43` | - |
| 270 | `src/Backend.elm:170-174` | - |
| 271 | `src/Helpers/GameLogic.elm:421-422` | getTileSideIds lastPlacedTile |
| 273 | `src/Helpers/GameLogic.elm:431-432` | -- Cities that are larger than 2 tiles give 2x points if they are completed before the game ends |
| 274 | `src/Helpers/GameLogic.elm:434-435` | - |
| 275 | `src/Backend.elm:63-64` | case getPlayableTileFromDrawstack game.tileGrid shuffledTileDrawStack of |
| 276 | `src/Backend.elm:76-77` | - |
| 277 | `src/Views/GameView.elm:159` | - |
| 278 | `src/Views/GameView.elm:29` | case game.gameState of |
| 280 | `src/Backend.elm:61-62` | - |
| 292 | `src/Backend.elm:52` | { game |
| 292 | `src/Backend.elm:56-57` | in |
| 338 | `src/Types.elm:25-28` | } |
| 338 | `src/Frontend.elm:165-166` | - |
| 338 | `src/Views/PlayerLobbyView.elm:11-24` | - |
| 338 | `src/Types/Game.elm:43-45` | - |
| 340 | `src/Types.elm:54` | | KillLobby |
| 341 | `src/Backend.elm:140` | - |
| 343 | `src/Backend.elm:140-146` | - |
| 343 | `src/Types/Game.elm:120-147` | -} |
| 343 | `src/Types/Game.elm:102-104` | -} |
| 344 | `src/Types.elm:63` | = ClientConnected SessionId ClientId |
| 345 | `src/Backend.elm:44-47` | - |
| 346 | `src/Helpers/FrontendHelpers.elm:136-137` | first :: rest -> |
| 346 | `src/Backend.elm:49-54` | - |
| 348 | `src/Backend.elm:58-59` | ( BeGamePlayed { game = updatedGame } |
| 349 | `src/Frontend.elm:134-141` | - |
| 349 | `src/Frontend.elm:155-156` | - |
| 351 | `src/Types/Game.elm:63-67` | , players = Array.fromList players |
| 359 | `src/Backend.elm:140-145` | - |
| 361 | `src/Helpers/FrontendHelpers.elm:142-143` | - |
| 363 | `src/Backend.elm:44-45` | - |
| 367 | `src/Backend.elm:40-42` | case ( msg, model ) of |
| 367 | `src/Frontend.elm:95-96` | case ( msg, model ) of |
| 374 | `src/Frontend.elm:56-57` | in |
| 375 | `src/Backend.elm:95-102` | let |
| 376 | `src/Backend.elm:110-118` | in |
| 376 | `src/Frontend.elm:112-115` | - |
| 376 | `src/Views/PlayerRegistrationView.elm:29-37` | ] |
| 423 | `src/Frontend.elm:34-41` | - |
| 423 | `src/Frontend.elm:47-48` | case ( msg, model ) of |
| 423 | `src/Frontend.elm:162-163` | case model of |
| 423 | `src/Views/PlayerRegistrationView.elm:11-28` | - |
| 424 | `src/Frontend.elm:50-57` | - |
| 424 | `src/Views/PlayerRegistrationView.elm:15-27` | [ div [] |
| 425 | `src/Views/PlayerRegistrationView.elm:40-45` | ] |
| 426 | `src/Frontend.elm:59-62` | - |
| 426 | `src/Types.elm:51` | type ToBackend |
| 427 | `src/Backend.elm:93-99` | case ( msg, model ) of |
| 428 | `src/Backend.elm:99-102` | in |
| 429 | `src/Backend.elm:105-110` | else |
| 430 | `src/Backend.elm:106-111` | let |
| ... | 182 more | |



## Semantic Findings (advisory)

Source: semantic tester (role `agents/06-verifier.md`, read-only explore subagent), 2026-09-15. Spot-checked ~45 citations across the six artifacts and ran cross-document consistency checks (entity sets, actors, process ↔ use-case ↔ feature alignment, naming). Advisory findings never block delivery; the mechanical citation/section/Mermaid verification above is independent and passes.

Raw tester output (verbatim):

```json
{
  "status": "ok",
  "findings": [
    {"id": "S-1", "severity": "blocker", "check": "entity_alignment",
     "docs": ["DatabaseModel.md", "DomainModel.md"],
     "locations": ["DatabaseModel.md §5.4 (line 342) and §9 seed table (line 580)", "DomainModel.md §2 glossary item 2 (line 25)", "code: src/Helpers/TileMapper.elm:12-19 (tile 0: City/Road/Field/Road, cloister = Nothing); cloisters are tiles 3 and 4 (TileMapper.elm:49,59)"],
     "finding": "DatabaseModel describes the starting tile (id 0 at (0,0)) twice as a 'center Cloister tile', while DomainModel describes it as 'city center with road' and the code shows tile 0 has cloister = Nothing (its sides are City/Road/Field/Road).",
     "likely_wrong": "DatabaseModel.md §5.4/§9 — code has tile 0 cloister=Nothing; cloister tiles are 3 and 4, so the 'Cloister' characterization is wrong"},
    {"id": "S-2", "severity": "minor", "check": "relationship",
     "docs": ["DomainModel.md", "DatabaseModel.md", "ClassModel.md"],
     "locations": ["DomainModel.md §5 relationship R5 (line 145) and class diagram", "DatabaseModel.md §4 ERD R1-R19 and §6 (lines 118-136, 454-537)", "ClassModel.md §5 CL-R1..CL-R33 (lines 699-735)"],
     "finding": "DomainModel's R5 Tile→Tile M:N 'connected features via SideId' has no counterpart edge in the DatabaseModel ERD or ClassModel relationships, where feature connectivity appears only as a prose note on Side.sideId grouping — a reader comparing the ERD with DomainModel §5 will not find the M:N edge.",
     "likely_wrong": "None — the ERD models persisted fields and the M:N is a derived relation; the DB model documents it in §6/§15, so this is a notational gap, not a contradiction"},
    {"id": "S-3", "severity": "minor", "check": "process_alignment",
     "docs": ["ActivityDiagram.md", "UseCaseModel.md", "Specification.md"],
     "locations": ["ActivityDiagram.md PR-5 entry points and nodes PR-5-N11..N16 (lines 453-523)", "UseCaseModel.md §6.3 'Terminate Game is out of scope' (line 500)", "Specification.md §4 UC table '— (not modeled as a UC)' (line 97) and §12 item 16 (line 201)"],
     "finding": "PR-5's TerminateGame branch (src/Backend.elm:180-183) is the only process fragment with no use case: TerminateGame is explicitly out of UC scope in both UseCaseModel and Specification, so process→use-case traceability has one documented orphan (the UC→process direction is complete, with UC-02/05/08 exclusions explicitly scoped in ActivityDiagram §3/§6).",
     "likely_wrong": "None — both sides state the scope decision explicitly; advisory traceability note only"}
  ],
  "summary": "The six documents describe one coherent system (Lamdera/Elm Carcassonne, no DB): actors, entities, cardinalities, stack, and ~45 spot-verified citations agree, and the plan's '74 tiles' error is consistently flagged as 24 designs/71-tile stack. One genuine contradiction: DatabaseModel calls the starting tile (id 0) a 'Cloister tile' although code (TileMapper.elm:12-19) has cloister=Nothing and DomainModel correctly calls it a city/road tile."
}
```

Disposition:

| ID | Severity | Status |
| :-- | :------- | :----- |
| S-1 | blocker (factual) | **FIXED post-hoc by orchestrator** — DatabaseModel.md §5.4 (line 342) and §9 seed table (line 580) both called the starting tile (id 0) a "center Cloister tile"; the code (`src/Helpers/TileMapper.elm:12-20`) shows tile 0 is City/Road/Field/Road with `cloister = Nothing`, and the cloister designs are tiles 3 and 4 (`src/Helpers/TileMapper.elm:42-60`). Both mentions corrected and now cite `src/Helpers/TileMapper.elm:12-20`; mechanical verification re-run after the edit (`verify-run3.log`). |
| S-2 | minor | Advisory only — notational gap (DomainModel R5 M:N edge absent from the ERD; the relation is derived, documented in DatabaseModel §6/§15). No contradiction. |
| S-3 | minor | Advisory only — TerminateGame is an explicitly scoped-out use case; the scope decision is stated in both UseCaseModel §6.3 and Specification §4/§12. |
