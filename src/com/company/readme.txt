Huy Le
COMP596: Cryptography
Cryptography Assignment 1

Use Kasiski method to break the cipher text
    https://crypto.interactive-maths.com/kasiski-analysis-breaking-the-code.html
        -> ex) of kasiski code breaking
Allow user to input a cipher text and get plain text as output

Instructions
Enter a cipher text when prompted.

Here are two ciphertexts provided for demo:

cipherText below is a copy from the website link listed above. The keyword for this cipher text is "brutus".
CVJTNAFENMCDMKBXFSTKLHGSOJWHOFUISFYFBEXEINFIMAYSSDYYIJNPWTOKFRHWVWTZFXHLUYUMSGVDURBWBIVXFAFMYFYXPIGBHWIFHHOJBEXAUNFIYLJWDKNHGAOVBHHGVINAULZFOFUQCVFBYNFTYGMMSVGXCFZFOKQATUIFUFERQTEWZFOKMWOJYLNZBKSHOEBPNAYTFKNXLBVUAXCXUYYKYTFRHRCFUYCLUKTVGUFQBESWYSSWLBYFEFZVUWTRLLNGIZGBMSZKBTNTSLNNMDPMYMIUBVMTLOBJHHFWTJNAUFIZMBZLIVHMBSUWLBYFEUYFUFENBRVJVKOLLGTVUZUAOJNVUWTRLMBATZMFSSOJQXLFPKNAULJCIOYVDRYLUJMVMLVMUKBTNAMFPXXJPDYFIJFYUWSGVIUMBWSTUXMSSNYKYDJMCGASOUXBYSMCMEUNFJNAUFUYUMWSFJUKQWSVXXUVUFFBPWBCFYLWFDYGUKDRYLUJMFPXXEFZQXYHGFLACEBJBXQSTWIKNMORNXCJFAIBWWBKCMUKIVQTMNBCCTHLJYIGIMSYCFVMURMAYOBJUFVAUZINMATCYPBANKBXLWJJNXUJTWIKBATCIOYBPPZHLZJJZHLLVEYAIFPLLYIJIZMOUDPLLTHVEVUMBXPIBBMSNSCMCGONBHCKIVLXMGCRMXNZBKQHODESYTVGOUGTHAGRHRMHFREYIJIZGAUNFZIYZWOUYWQZPZMAYJFJIKOVFKBTNOPLFWHGUSYTLGNRHBZSOPMIYSLWIKBANYUOYAPWZXHVFUQAIATYYKYKPMCEYLIRNPCDMEIMFGWVBBMUPLHMLQJWUGSKQVUDZGSYCFBSWVCHZXFEXXXAQROLYXPIUKYHMPNAYFOFHXBSWVCHZXFEXXXAIRPXXGOVHHGGSVNHWSFJUKNZBESHOKIRFEXGUFVKOLVJNAYIVVMMCGOFZACKEVUMBATVHKIDMVXBHLIVWTJAUFFACKHCIKSFPKYQNWOLUMYVXYYKYAOYYPUKXFLMBQOFLACKPWZXHUFJYGZGSTYWZGSNBBWZIVMNZXFIYWXWBKBAYJFTIFYKIZMUIVZDINLFFUVRGSSBUGNGOPQAILIFOZBZFYUWHGIRHWCFIZMWYSUYMAUDMIYVYAWVNAYTFEYYCLPWBBMVZZHZUHMRWXCFUYYVIENFHPYSMKBTMOIZWAIXZFOLBSMCHHNOJKBMBATZXXJSSKNAULBJCLFWXDSUYKUCIOYJGFLMBWHFIWIXSFGXCZBMYMBWTRGXXSHXYKZGSDSLYDGNBXHAUJBTFDQCYTMWNPWHOFUISMIFFVXFSVFRNA

cipherText below is a song called Box of Rain by the Grateful Dead. The keyword for this cipher should result as "boxofrain"
mclytltwsbbvknedwjbbvatinqahokmjmevvouxbduagzbmysyyeahowpgmznqahpffijazrxwkunegwesofbnjfiymwkukiounisxjdjkgjioqrtpocjbbqajkolbucackfrgbvhlgjvywhuvoczxhnbshewxzsiymoafjrmerefborvdwafochjinwbozlblrgwjbzhczkonnomactiwilgsbzdfuzjbmcsjcywhskxmqzkmgisaodsenbssjodsegbvzitnedlvsszhnfniepikrxfmmppfkswnhmefwqggvevjbwqwsxtwzfsqmtlwpnurlmtlwiauabhtuobbxoqqmwozlpitvncegbvfbgqvexvouqvjeptrbgbrtetjrtiodwzsmqxvbbdfunvorjsiieizjbdhtflwblwkhtrngrzspmtlfqaepvmtlywhdokgjvctrbfqvwfuouucxbtkhmeeovafpbmvugysjesmropbttiebuscrumftprssvsxfnwgisorfpseujzbutznoupabkmrtlbzcrkfeturucacyfdwspfvczkoarfmliyyrwhhvfhxrltnefbornelefojsifnmnghbfsfovypbdolfwiylwkhtjptvohbfjuscamwdvyznkuzcrfbrybuscrumueiqefborjtwnocqvjiliaeaxmgvywhssqwwvdiaepocpvngbvfqcsxumvthtwxkeljjhektidaubzcgufkmabbahmfuouugrbhceiexvxhifywhxokhrvtwqphlrtwozlpiqcxvegbvheftlgpnccuckiaqaxwizjrsmgismoneavqmcssbzltffsvczkhzbvuexzjtioplltwrivjjbaosuwigffysqzedrjhftdfuvrfrfhnwywheckholsbcbgpwyfnahookrxyoerskfbirnlebwkwsrnlbvhqvjnivqpkiwpvaubuvyskfrmngzxajrnlvuggixkajbyccffznqqpbqysfweupdrhnktprssysqzedrjhftdfuvrfrfhtilmnwsfhnwywheoosfedqgtxrgyrbwkptooneoznswyptefwezcrfmrizfvqeoqfnoypbdhndebbcsdcsvavqbgecwktqzfhlpjkhmef

notes
This program was written to only:
- find patterns with a length of 3 and 4
- use max key length was no greater than 96
- determine the 5 most common factors and display all relevant decryption information with these factors as lengths
- use one of these key lengths should display the correct plain text but will require human interaction to pick out the proper one

could not figure out an algorithm to determine the proper key length. was stuck in a situation where key length 3 would be selected but 6 should have been the key length.