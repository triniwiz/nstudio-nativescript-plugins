<page>
    <actionBar title="nativescript-exoplayer" />
    <gridLayout>
        <button class="info" text="{message}" horizontalAlignment="center" verticalAlignment="middle" textWrap="true"/>
    </gridLayout>
</page>

<script lang="typescript">
    import { DemoSharedNativescriptExoplayer } from '@demo/shared';
    import { } from '@nstudio/nativescript-exoplayer';

    let message: string = "Test nativescript-exoplayer"
</script>

<style>
    .info {
        font-size: 20;
    }
</style>
