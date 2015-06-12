CM12.1 Manifest - Project Vee3
========================
Local manifests to build Android Lollipop 5.1 to L3 II Single/Dual

To initialize CM12.1 Repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-12.1

To initialize Vee3 Repo's:

    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.github.com/TeamVee/android_.repo_local_manifests/cm-12.1/local_manifest.xml

To sync:

    repo sync
