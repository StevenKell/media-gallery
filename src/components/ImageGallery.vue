<template>
    <v-container fluid>
        <VRow>
            <VCol v-for="n in 12" cols="3">
                <VCard>
                    hello
                    <VImg 
                    :src="require('@/assets/images/callForSponsors.png')"
                    >

                    </VImg>
                </VCard>
            </VCol>
        </VRow>
    </v-container>
</template>