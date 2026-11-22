WITHER FORM - MINECRAFT JAVA 26.3 (FABRIC)

This archive contains the Wither Form mod source project and a GitHub Actions
workflow configured to build with Java 25 and Gradle 9.8.2.

IMPORTANT: This is the SOURCE PROJECT, not a compiled .jar. A successful
GitHub Actions build is still required before installing it in Minecraft.

BUILD ON GITHUB
1. Upload the contents of the witherform folder into the root of your GitHub repo.
2. Ensure .github/workflows/build.yml is present in the repo.
3. Open Actions -> Build mod -> Run workflow.
4. When the run succeeds, download the witherform-jar artifact.
5. Put the resulting .jar in your Minecraft instance's mods folder, along with
   Fabric API, and launch Minecraft 26.3 with Fabric Loader.

The project requires Java 25. If the build fails, open the failed Build step
and inspect the final error lines; the source may need API adjustments.
