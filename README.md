# Silent Dragon Wormhole

Wormhole Service for SilentDragon mobile app at wormhole.myhush.org

# Compiling From Source

Install dependencies:

    sudo apt-get install android-sdk gradle

Your system may have a version of gradle that is too old. Gradle 5.6.1 is known
to work well:

    wget https://services.gradle.org/distributions/gradle-5.6.1-bin.zip
    unzip gradle-5.6.1-bin.zip
    export PATH=$HOME/gradle-5.6.1-bin:$PATH

Clone and compile:

    git clone https://github.com/MyHush/SilentDragonWormhole
    cd SilentDragonWormhole
    gradle build

# Running the Wormhole

If the build was successful, you can execute the binary and start the server:

    java -jar build/libs/wormhole-1.0-SNAPSHOT.jar

Note: The default port of the Wormhole is 7070. This can be changed in source and recompiled if needed.

# License

MIT

# Authors

Hush Core developers
Zecwallet developers
