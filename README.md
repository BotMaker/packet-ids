# packet-ids
requires 

euphoria 3.1

AS3 Sorcerer Save All Scripts to Single File... command

goto 
http://www.realmofthemadgod.com/version.txt

get the version number "1375118885" 

change the url version number to the current version

goto
http://www.realmofthemadgod.com/AssembleeGameClient1375118885.swf

you can then save the client.swf from within the browser, via menu file save

open the client.swf in AS3 Sorcerer run the Save All Scripts to Single File
for use in packet id.exw, used to get the new upto-date packet id numbers



        public static const BUILD_VERSION:String = "X29.0";
        public static const MINOR_VERSION:String = "1";
        public static const ENABLE_ENCRYPTION:Boolean = true;
        public static const PORT:int = 2050;
        public static const ALLOW_SCREENSHOT_MODE:Boolean = false;
        public static const USE_NEW_FRIENDS_UI:Boolean = true;
        public static const FELLOW_GUILD_COLOR:uint = 10944349;
        public static const NAME_CHOSEN_COLOR:uint = 0xFCDF00;
        public static var root:DisplayObject;
        public static const PLAYER_ROTATE_SPEED:Number = 0.003;
        public static const BREATH_THRESH:int = 20;
        public static const SERVER_CHAT_NAME:String = "";
        public static const CLIENT_CHAT_NAME:String = "*Client*";
        public static const ERROR_CHAT_NAME:String = "*Error*";
        public static const HELP_CHAT_NAME:String = "*Help*";
        public static const GUILD_CHAT_NAME:String = "*Guild*";
        public static const NEWS_TIMESTAMP_DEFAULT:Number = 1.1;
        public static const NAME_CHANGE_PRICE:int = 1000;
        public static const GUILD_CREATION_PRICE:int = 1000;
        public static var data_:Object = null;
        public static var GPURenderError:Boolean = false;
        public static var sessionStarted:Boolean = false;
        public static var blendType_:int = 1;
        public static var projColorType_:int = 0;
        public static var drawProj_:Boolean = true;
        public static var screenShotMode_:Boolean = false;
        public static var screenShotSlimMode_:Boolean = false;
        public static var sendLogin_:Boolean = true;
        public static const TUTORIAL_GAMEID:int = -1;
        public static const NEXUS_GAMEID:int = -2;
        public static const RANDOM_REALM_GAMEID:int = -3;
        public static const MAPTEST_GAMEID:int = -6;
        public static const MAX_SINK_LEVEL:Number = 18;
        public static const TERMS_OF_USE_URL:String = "http://legal.decagames.com/tos/";
        public static const PRIVACY_POLICY_URL:String = "http://legal.decagames.com/privacy/";
        public static const USER_GENERATED_CONTENT_TERMS:String = "/UGDTermsofUse.html";
        public static const RANDOM1:String = "311f80691451c71b09a13a2a6e";
        public static const RANDOM2:String = "72c5583cafb6818995cbd74b80";
        public static const RSA_PUBLIC_KEY:String = ((((("-----BEGIN PUBLIC KEY-----\n" + "MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQDCKFctVrhfF3m2Kes0FBL/JFeO") + "cmNg9eJz8k/hQy1kadD+XFUpluRqa//Uxp2s9W2qE0EoUCu59ugcf/p7lGuL99Uo") + "SGmQEynkBvZct+/M40L0E0rZ4BVgzLOJmIbXMp0J4PnPcb6VLZvxazGcmSfjauC7") + "F3yWYqUbZd/HCBtawwIDAQAB\n") + "-----END PUBLIC KEY-----");
        private static var savedOptions_:SharedObject = null;
        public static const skinTypes16:Vector.<int> = new <int>[1027, 0x0404, 1029, 1030, 10973, 19494, 19531, 6346, 30056];
        public static const itemTypes16:Vector.<int> = new <int>[5473, 5474, 5475, 5476, 10939, 19494, 19531, 6347];
        private static var keyNames_:Dictionary = new Dictionary();
